
# Breast Cancer Classification using Logistic Regression

## Project Overview
This project implements a Machine Learning model using Logistic Regression to classify breast cancer tumors into two categories: Benign and Malignant.

The model is trained using the Breast Cancer dataset and applies data preprocessing, feature scaling, model training, and evaluation techniques to achieve accurate classification.

## Objectives
- Implement Logistic Regression for binary classification.
- Perform data preprocessing and feature scaling.
- Predict Benign and Malignant tumor categories.
- Evaluate model performance using different metrics.
- Visualize the Confusion Matrix and ROC Curve.
- Analyze important features using model coefficients.

## Dataset
**Dataset:** Breast Cancer Dataset

**Target Classes:**
- 0 – Benign (Non-cancerous)
- 1 – Malignant (Cancerous)

The dataset contains numerical features such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm
**Logistic Regression**

Logistic Regression is a supervised Machine Learning algorithm used for binary classification. It predicts the probability of a data point belonging to a particular class.

## Project Workflow
1. Dataset Loading
2. Data Exploration
3. Missing Value Checking
4. Duplicate Record Checking
5. Data Preprocessing
6. Feature and Target Separation
7. Train-Test Split (80:20)
8. Feature Scaling using StandardScaler
9. Logistic Regression Model Training
10. Model Prediction
11. Model Evaluation
12. Confusion Matrix Visualization
13. ROC Curve Analysis
14. Feature Importance Analysis

## Model Performance

The Logistic Regression model achieved the following results:

| Evaluation Metric | Score |
|-------------------|-------|
| Accuracy | 96% |
| Weighted Precision | 0.97 |
| Weighted Recall | 0.96 |
| Weighted F1-Score | 0.96 |
| ROC-AUC Score | 0.9960 |

### Classification Report

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Benign | 0.96 | 0.99 | 0.97 |
| Malignant | 0.97 | 0.93 | 0.95 |

### ROC Curve
The model achieved an ROC-AUC score of **0.9960**, indicating excellent ability to distinguish between Benign and Malignant classes on the test dataset.

### Feature Importance
The top 10 features based on absolute Logistic Regression coefficients are:

1. texture_worst
2. radius_se
3. symmetry_worst
4. concave points_mean
5. concavity_worst
6. area_se
7. compactness_se
8. area_worst
9. radius_worst
10. concavity_mean

## Results and Conclusion
The Logistic Regression model successfully classified breast cancer cases into Benign and Malignant categories with an accuracy of 96%.

The ROC-AUC score of 0.9960 demonstrates excellent classification performance on the test dataset. Feature coefficient analysis also identified the measurements that contributed most strongly to the model's predictions.

This project demonstrates the practical application of Logistic Regression for binary classification and highlights the importance of data preprocessing, feature scaling, and model evaluation in Machine Learning.

## Repository Structure

```text
Breast-Cancer-Classification/
│
├── Logistic_Regression.ipynb
├── breast cancer.csv
└── README.md
```

## Installation and Execution

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Project
Open `Logistic_Regression.ipynb` and execute all cells sequentially.

Make sure the dataset CSV file is available at the path specified in the notebook.

## Author

**Utkrisht Patel**

B.Tech – Computer Science and Engineering

Researcher | Machine Learning | Data Science | IoT

---

**Disclaimer:** This project is developed for educational and research purposes only. It is not a clinically validated diagnostic system and should not be used for medical decision-making.
