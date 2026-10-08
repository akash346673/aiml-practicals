# AIML Practical Assignments

Python code for the 10 AIML practical assignments.

| # | Topic | File |
|---|-------|------|
| 01 | Association between variables (correlation + Linear Regression) | `01_correlation_linear_regression.py` |
| 02 | K-Means clustering (unsupervised) | `02_kmeans_clustering.py` |
| 03 | Dimensionality reduction using PCA | `03_pca_dimensionality_reduction.py` |
| 04 | Naive Bayes classification | `04_naive_bayes.py` |
| 05 | K-Nearest Neighbors classification | `05_knn_classification.py` |
| 06 | Linear Regression | `06_linear_regression.py` |
| 07 | Support Vector Regression | `07_support_vector_regression.py` |
| 08 | Ridge and Lasso regularization | `08_ridge_lasso_regularization.py` |
| 09 | Object detection from CCTV footage (YOLOv8) | `09_cctv_object_detection_yolo.py` |
| 10 | Multimodal fake news detection | `10_multimodal_fake_news_detection.py` |

## Setup

```bash
pip install -r requirements.txt
```

## Run

```bash
python 01_correlation_linear_regression.py
```

Assignment 09 needs a video file named `cctv_footage.mp4` in the same folder
(or change `video_path` in the script; use `0` for a webcam). The `yolov8n.pt`
weights download automatically on first run.
