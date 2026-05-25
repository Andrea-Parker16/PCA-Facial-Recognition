
# Facial Recognition using PCA and Eigenfaces

## Overview
This project implements a facial recognition system using the Eigenfaces method and Principal Component Analysis (PCA) in GNU Octave.

The system reduces high-dimensional facial image data into lower-dimensional representations while maintaining important facial characteristics for classification.

---

## Features
- Facial image preprocessing
- PCA dimensionality reduction
- Eigenface generation
- Face projection into eigenspace
- Nearest-neighbor classification
- Statistical performance evaluation

---

## Technologies Used
- GNU Octave
- Principal Component Analysis (PCA)
- Linear Algebra
- Euclidean Distance Classification
- Matrix Operations

---

## Methodology

### 1. Image Preprocessing
Facial images are converted into grayscale vectorized numerical representations.

### 2. Principal Component Analysis
PCA reduces dimensionality by extracting principal components from the covariance matrix.

### 3. Eigenface Generation
Eigenvectors with the largest eigenvalues are selected to represent dominant facial features.

### 4. Face Projection
Images are projected into eigenspace for compact feature representation.

### 5. Classification
A nearest-neighbor classifier compares projected test images using Euclidean distance.

---

## Results
The system successfully:
- Generated mean face visualizations
- Produced eigenfaces
- Reduced computational complexity
- Classified facial images with strong accuracy

---

## Evaluation Metrics
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Accuracy

---

## Lessons Learned
This project strengthened understanding of:
- Machine Learning Foundations
- Computer Vision
- Scientific Computation
- Applied Linear Algebra
- Statistical Evaluation Techniques

---

## Future Improvements
- Implement Support Vector Machines (SVM)
- Add deep learning-based face recognition
- Improve robustness under varying lighting conditions
- Expand dataset size

---

## Author
Andrea Parker
