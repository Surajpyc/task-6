# K-Nearest Neighbors (KNN) Classification on Iris Dataset

## Objective
Understand and implement KNN for classification problems using the Iris dataset.

## Tools
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Steps

### 1. Import Libraries
Essential libraries are imported for data manipulation, modeling, and visualization.

### 2. Load and Prepare the Data
- Load `Iris.csv`.
- Drop the 'Id' column if present.
- Separate features (X) and labels (y).

### 3. Normalize Features
- Standardize the features using `StandardScaler`.

### 4. Train-Test Split
- Split the dataset into training and test sets (80/20 split).

### 5. Experiment with Different Values of K
- Train KNN models with different values of K.
- Plot accuracy against K.

### 6. Final Model Evaluation
- Choose the best K.
- Train the final model and evaluate it using accuracy and confusion matrix.

### 7. Visualize Decision Boundaries (Optional)
- Visualize decision boundaries using the first two features of the dataset.

## How to Run
Run the Python code blocks sequentially in a Jupyter Notebook or Python script environment.

## Dataset
Ensure `Iris.csv` is in your working directory.

---

This project demonstrates how to implement and evaluate a simple K-Nearest Neighbors classifier on a standard classification dataset.
