# Logistic Regression for Cancer Detection

## Project Overview
This project uses **Logistic Regression** to predict whether a breast tumor is **benign** or **malignant** based on medical features.  
The goal is to demonstrate the complete **machine learning workflow**, including data preparation, model training, evaluation, and result interpretation.

The project focuses on understanding how classification models work in real-world medical decision support systems.

---

## Dataset Description
The project uses the **Breast Cancer Wisconsin dataset**, which contains measurements computed from digitized images of breast mass biopsies.

- Number of samples: 569  
- Number of features: 30  
- Target variable:
  - `0` → Malignant tumor
  - `1` → Benign tumor

The dataset contains **no missing values**, making it suitable for introductory machine learning experiments.

---

## Features Used
The input features include numerical medical measurements such as:
- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Mean smoothness
- Compactness, concavity, symmetry, and related statistics

These features describe the physical characteristics of cell nuclei and are useful indicators for tumor classification.

---

## Machine Learning Workflow
The following steps were followed in this project:

1. Load and inspect the dataset
2. Separate features (X) and target variable (y)
3. Scale features using StandardScaler
4. Split data into training and testing sets (70% / 30%)
5. Train a Logistic Regression model
6. Make predictions on the test set
7. Evaluate the model using:
   - Accuracy
   - Confusion matrix
   - Classification report

---

## Model Evaluation
The Logistic Regression model achieved **high accuracy**, indicating strong performance in distinguishing between benign and malignant tumors.

- Accuracy measures overall correctness
- Confusion matrix shows correct and incorrect predictions
- Classification report provides precision, recall, and F1-score

The results demonstrate that Logistic Regression is effective for this binary classification problem.

---

## Key Findings
- Feature scaling improves model performance
- Logistic Regression performs well on linearly separable medical data
- The model achieves high precision and recall, which is important in medical applications
- Misclassifications are minimal but still represent real-world risk

---

## How to Run the Notebook
1. Open the notebook in **Jupyter Notebook** or **Google Colab**
2. Run all cells from top to bottom
3. Ensure required libraries are installed:
   - pandas
   - numpy
   - scikit-learn
   - matplotlib (optional, for visualization)

---

## Limitations
- The dataset is relatively small
- The model is trained on structured numerical data only
- Real-world deployment would require further validation and ethical review

---

## Conclusion
This project demonstrates how Logistic Regression can be applied to medical data for cancer detection.  
It highlights the importance of proper data preparation, evaluation metrics, and responsible use of machine learning in healthcare.

