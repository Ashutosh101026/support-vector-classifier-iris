# Iris Flower Classification using Support Vector Machine (SVM)

## Project Overview

This project implements a Support Vector Machine (SVM) classifier using Scikit-Learn to classify Iris flowers into three species based on their physical characteristics.

The project demonstrates data preprocessing, feature scaling, model training, hyperparameter tuning, prediction, and performance evaluation using the Iris dataset.

---

## Dataset Information

**Dataset:** Iris Dataset

**Source:** Scikit-Learn Built-in Dataset

**Number of Samples:** 150

**Number of Features:** 4

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

## Project Workflow

### 1. Data Loading

- Loaded the Iris dataset using Scikit-Learn.
- Converted the dataset into a Pandas DataFrame.

### 2. Exploratory Data Analysis

- Dataset inspection
- Feature analysis
- Class distribution analysis

### 3. Data Preprocessing

- Feature selection
- Feature scaling using StandardScaler

### 4. Train-Test Split

- Training Data: 70%
- Testing Data: 30%

### 5. Model Development

Implemented Support Vector Classifier (SVC) using Scikit-Learn.

### 6. Hyperparameter Tuning

To improve classification performance, multiple values of the regularization parameter **C** were evaluated.

```python
C_values = [0.5, 1, 2, 3, 4, 5]
```

The model was trained and tested for each value of C, and the best-performing configuration was selected based on classification accuracy.

### 7. Model Evaluation

Performance metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report

### 8. Prediction

The trained model was used to predict Iris flower species on unseen test samples.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Machine Learning Algorithm

### Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification tasks. It identifies the optimal decision boundary that maximizes the separation between classes.

#### Advantages

- High classification accuracy
- Effective in high-dimensional spaces
- Robust against overfitting
- Excellent performance on small and medium-sized datasets

---

## Results

The Support Vector Machine successfully classified Iris flower species with high accuracy. Hyperparameter tuning helped identify the optimal value of C and improved model performance.

---

## Learning Outcomes

- Support Vector Machines (SVM)
- Multiclass Classification
- Feature Scaling
- Hyperparameter Tuning
- Model Selection
- Confusion Matrix Analysis
- Classification Report Interpretation
- Model Evaluation

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Run the Project

```bash
jupyter notebook
```

Open:

```text
SVC_on_iris_dataset.ipynb
```

---

## Project Structure

```text
iris-flower-classification-using-svm
│
├── SVC_on_iris_dataset.ipynb
├── README.md
└── requirements.txt
```

---

## Future Improvements

- GridSearchCV for automated hyperparameter optimization
- Cross Validation
- PCA for dimensionality reduction
- Comparison with KNN Classifier
- Comparison with Random Forest Classifier
- Streamlit Deployment

---

## Author

Ashutosh Mehta

Computer Engineering Student

Machine Learning Enthusiast
