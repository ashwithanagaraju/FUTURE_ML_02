
# Customer Churn Prediction System

This repository contains a machine learning project focused on predicting customer churn using historical customer data. Customer churn prediction is a critical business problem, as retaining existing customers is significantly more cost-effective than acquiring new ones. The project is developed as part of Future Interns – Machine Learning Task 2 and follows industry-standard practices for data analysis, modeling, and version control.

## Dataset
The project uses the Telco Customer Churn dataset sourced from Kaggle. The dataset includes customer demographic information, service subscriptions, contract details, billing data, and payment methods. The target variable is `Churn`, which indicates whether a customer has discontinued the service.

## Methodology
An end-to-end machine learning workflow is implemented in this project. This includes exploratory data analysis to understand customer behavior, data preprocessing and feature engineering, training and evaluation of multiple classification models, and selection of a final model based on performance and interpretability. All detailed analysis and experimentation are documented in the Jupyter notebooks included in the repository.

## Repository Structure

FUTURE_ML_02/
├── data/
├── notebooks/
├── models/
├── requirements.txt
└── README.md


## Usage
Clone the repository, install the required dependencies, and execute the notebooks in sequence, starting with data exploration followed by model training.

```bash
pip install -r requirements.txt

## Tools

Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Jupyter Notebook, VS Code, Git, and GitHub are used in this project.

## Notes
Model evaluation metrics, visualizations, and insights are intentionally documented within the notebooks to keep the repository overview concise and professional.