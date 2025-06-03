# Task6
# KNN Classification with Iris Dataset 

This task implements the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset.

---

## Objective

To understand and implement KNN for classification problems using the Iris dataset. This includes:
- Data preprocessing and normalization
- Model training using `KNeighborsClassifier`
- Tuning K value
- Model evaluation using accuracy, confusion matrix, and classification report
- Visualizing decision boundaries

---

## Dataset

- **Dataset Used**: Iris Dataset
- **Location**: `/kaggle/input/iris/Iris.csv`
- **Target Variable**: `Species`
- **Features**:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm

---

## Steps Performed

1. **Loaded and explored** the dataset.
2. **Normalized** feature values using `StandardScaler`.
3. Used **KNeighborsClassifier** from `sklearn`.
4. **Trained the model** using various values of `k` (1 to 10).
5. Evaluated performance using:
   - Accuracy
   - Confusion matrix
   - Classification report
6. **Visualized decision boundaries** using 2D feature projection (`PetalLengthCm` vs `PetalWidthCm`).

---

##
