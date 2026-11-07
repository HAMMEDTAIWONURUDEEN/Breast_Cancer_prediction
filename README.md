# Breast_Cancer_prediction
# Breast Cancer Prediction Using Machine Learning

## Project Overview
This project focuses on building a machine learning classification model to classify breast cancer tumours as malignant or benign using features extracted from digitized images of breast mass samples.

The main objective is to explore how machine learning algorithms can learn patterns from medical data and make predictions based on tumour characteristics.

## Dataset Description
The project uses the Breast Cancer Wisconsin Diagnostic dataset from Scikit-learn.

- Total records: 569
- Number of features: 30
- Target variable: `diagnosis`

**Target Classes:**
- `0` – Malignant
- `1` – Benign

The dataset contains numerical measurements describing characteristics of cell nuclei, including radius, texture, perimeter, area, smoothness, compactness, and symmetry.

## Data Preprocessing and Exploration
The project involved:
- Checking for missing values.
- Checking and removing duplicate records where applicable.
- Examining feature distributions using histograms.
- Identifying potential outliers using boxplots.
- Exploring relationships between features using a correlation heatmap.
- Separating features from the target variable.
- Splitting the dataset into training, validation, and testing sets.

## Algorithms Implemented

### 1. Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees to make classification predictions.

Initial test accuracy: **89.53%**

### 2. Logistic Regression
A classification algorithm that estimates the probability of a sample belonging to a particular class.

StandardScaler was applied to standardize the numerical features before training.

Final test accuracy: **94.19%**

## Model Evaluation

The Logistic Regression model achieved the following results on the test split:

| Evaluation Metric | Malignant (0) | Benign (1) |
|---|---:|---:|
| Precision | 90.91% | 96.23% |
| Recall | 93.75% | 94.44% |
| F1-score | 92.31% | 95.33% |

**Overall Test Accuracy: 94.19%**

**Confusion Matrix:**

| | Predicted Malignant | Predicted Benign |
|---|---:|---:|
| Actual Malignant | 30 | 2 |
| Actual Benign | 3 | 51 |

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Key Learning Outcomes
Through this project, I gained practical experience in:
- Exploratory Data Analysis (EDA).
- Data preprocessing and feature examination.
- Binary classification.
- Random Forest and Logistic Regression.
- Feature scaling using StandardScaler.
- Training, validation, and testing.
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrices.
- Understanding the importance of false positives and false negatives in medical classification.

## Disclaimer
This project is strictly for educational and machine learning practice. It is not a clinically validated diagnostic system and must not be used to diagnose cancer or guide medical treatment.

## Author
Mechatronics Engineering Student | Machine Learning Enthusiast

