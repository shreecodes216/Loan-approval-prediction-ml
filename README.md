# 🏦 Loan Approval Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Random Forest](https://img.shields.io/badge/Model-Random%20Forest-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

An end-to-end **Machine Learning Classification Project** that predicts whether a loan application should be **Approved** or **Rejected** based on applicant information. The project demonstrates the complete ML workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation.

The final **Random Forest Classifier** achieved an accuracy of **92.87%**, outperforming Logistic Regression and Decision Tree models.

---

# 📌 Table of Contents

- Project Overview
- Objectives
- Dataset
- Technologies Used
- Machine Learning Workflow
- Exploratory Data Analysis
- Models Implemented
- Model Performance
- Feature Importance
- Repository Structure
- Installation
- Results
- Future Enhancements
- Author

---

# 📖 Project Overview

Financial institutions receive thousands of loan applications every day. Manual verification is time-consuming, resource-intensive, and may lead to inconsistent decisions.

This project develops a Machine Learning model capable of predicting whether a loan application should be approved based on applicant information such as income, credit history, loan amount, education, and employment details.

The project follows a complete Machine Learning pipeline from raw data preprocessing to final model evaluation.

---

# 🎯 Objectives

- Predict loan approval status using Machine Learning.
- Compare multiple classification algorithms.
- Identify important features affecting loan approval.
- Improve decision-making efficiency through automation.
- Achieve high prediction accuracy.

---

# 📂 Dataset

The dataset contains historical loan application records with applicant information.

### Features

- Age
- Gender
- Education
- Annual Income
- Employment Experience
- Home Ownership
- Loan Amount
- Loan Intent
- Interest Rate
- Loan Percentage of Income
- Credit History
- Credit Score
- Previous Loan Status
- Loan Status (Target Variable)

---

# 🛠️ Technologies Used

### Programming Language

- Python

### Development Environment

- Google Colab

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

# ⚙️ Machine Learning Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
Feature Engineering
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
(Logistic Regression,
Decision Tree,
Random Forest)
   │
   ▼
Model Evaluation
   │
   ▼
Feature Importance Analysis
   │
   ▼
Loan Approval Prediction
```

---

# 📊 Exploratory Data Analysis

Several visualization techniques were used to understand the dataset.

The project includes:

- Correlation Heatmap
- Loan Status Distribution
- Income Distribution
- Credit Score Distribution
- Feature Importance
- Accuracy Comparison
- Confusion Matrix

---

## 📷 Sample Visualizations

### Feature Importance

<img width="1217" height="667" alt="Feature Importance Graph" src="https://github.com/user-attachments/assets/8955ac76-b850-481d-abcb-67171d063e76" />


---

### Confusion Matrix

<img width="650" height="592" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/9e64a4f8-2b02-428f-9bf5-9e6fc812dade" />


---

### Correlation Heatmap

<img width="1052" height="972" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/d42db008-a59e-414c-add5-ed4b85626b80" />


---

# 🤖 Models Implemented

Three Machine Learning classification algorithms were implemented and compared.

| Model | Purpose |
|--------|----------|
| Logistic Regression | Baseline classification model |
| Decision Tree | Tree-based classification |
| Random Forest | Ensemble learning model |

---

# 📈 Model Performance

| Model | Accuracy |
|--------|-----------:|
| Logistic Regression | **82.70%** |
| Decision Tree | **89.81%** |
| Random Forest | **92.87%** ✅ |

The **Random Forest Classifier** achieved the highest prediction accuracy and was selected as the final model.

---

# ⭐ Feature Importance

The Random Forest model identified the following features as the most influential in predicting loan approval:

- Previous Loan
- Loan Percentage
- Loan Interest Rate
- Person Income

Feature importance analysis improves the interpretability of the model and helps understand the key factors influencing loan approval decisions.

---



# 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/loan-approval-prediction-ml.git
```

### Navigate to the project directory

```bash
cd loan-approval-prediction-ml
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open the notebook

Run the notebook in **Google Colab** or **Jupyter Notebook**.

```
loan_approval_prediction.ipynb
```

Execute all cells to reproduce the results.

---

# 📊 Results

- Successfully developed an end-to-end Machine Learning pipeline.
- Achieved **92.87% prediction accuracy** using Random Forest.
- Compared three supervised classification algorithms.
- Identified the key factors affecting loan approval decisions.
- Performed exploratory data analysis and feature importance analysis.
- Generated multiple visualizations for model interpretation.

---

# 💡 Skills Demonstrated

- Machine Learning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Classification
- Random Forest
- Logistic Regression
- Decision Tree
- Model Evaluation
- Data Visualization
- Python Programming

---

# 🔮 Future Enhancements

- Develop a Streamlit web application.
- Deploy the model to the cloud.
- Perform hyperparameter tuning.
- Implement Explainable AI using SHAP/LIME.
- Add real-time prediction interface.
- Improve model performance using advanced ensemble algorithms.

---

# 📄 Documentation

The repository includes:

- 📘 Technical Documentation
- 📑 Project Report
- 📓 Google Colab Notebook
- 📊 Dataset
- 📈 Visualization Images

> **Note:** The trained model (`loan_approval_model.pkl`) is not included in this repository. Running the notebook will train the model and regenerate the saved model file.

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork this repository and submit a pull request.

---

# 👩‍💻 Author

**Somoshree Pal**

_ECE Udergraduate_


---


# 📜 License

This project is licensed under the MIT License.


---



## ⭐ If you found this project useful, consider giving it a Star!



