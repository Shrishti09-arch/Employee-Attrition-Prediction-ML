# Employee Attrition Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## Project Overview

Employee attrition is one of the biggest challenges faced by organizations because losing experienced employees results in increased recruitment costs, reduced productivity, and loss of organizational knowledge.

This project develops an end-to-end Machine Learning solution capable of predicting whether an employee is likely to leave the organization based on demographic, professional, and workplace-related factors.

The project demonstrates the complete Data Science workflow from data preprocessing to business recommendations.

---

## Business Problem

Organizations spend significant resources recruiting and training employees. Identifying employees who are likely to leave enables Human Resource departments to implement proactive retention strategies before attrition occurs.

---

## Dataset

**IBM HR Analytics Employee Attrition Dataset**

- Total Employees: 1470
- Features: 35+
- Target Variable:
  - 1 → Employee Left
  - 0 → Employee Stayed

---

## Project Workflow

- Data Loading
- Data Exploration
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Preprocessing
- Machine Learning
- Model Evaluation
- Feature Importance
- Business Insights
- HR Recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models

The following classification models were implemented:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## Evaluation Metrics

The models were compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## Exploratory Data Analysis

The project investigates:

- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition
- Correlation Heatmap

---

## Key Business Insights

- Sales department experiences the highest employee attrition.
- Sales Representatives and Laboratory Technicians exhibit higher turnover rates.
- Employees with lower monthly income are more likely to leave.
- Lower work-life balance and overtime contribute significantly to attrition.
- Most resignations occur during the early years of employment.

---

## HR Recommendations

- Prioritize retention initiatives within high-risk departments.
- Improve employee engagement during the first few years.
- Review overtime policies.
- Strengthen career growth opportunities.
- Monitor employee satisfaction regularly.

---

## Project Structure

```text
Employee-Attrition-Prediction-ML/
│
├── analysis.ipynb
├── summary.docx
├── HR_Attrition.csv
├── requirements.txt
├── README.md
│
└── charts/
```

---

## How to Run

Clone the repository

```bash
git clone https://github.com/YourUsername/Employee-Attrition-Prediction-ML.git
```

Move into the project

```bash
cd Employee-Attrition-Prediction-ML
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
analysis.ipynb
```

---

## Future Improvements

- XGBoost implementation
- LightGBM implementation
- Hyperparameter tuning
- Streamlit Dashboard
- SHAP Explainability
- Real-time prediction interface

---

## Author

**Shrishti Vaishnav**

B.Tech – Mathematics & Computing

Passionate about Machine Learning, Data Science, Artificial Intelligence and Analytics.

---

## Acknowledgements

IBM HR Analytics Dataset

Scikit-Learn

Pandas

NumPy

Matplotlib

Seaborn

---

## License

This project is licensed under the MIT License.
