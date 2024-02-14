# SYRIATEL-DATA
# Customer churn prediction model

## Project Overview
This project involved building a model that would best predict the likelihood of a customer to churn based on key features from the SyriaTel dataset. The goal was to create a feasible churn prediction model for Syria Telecommunication company that would help the company in mitigating the customer churn.

The model focuses on understanding:
- How different customer  behaviors contribute to churning.
- Which customer behaviors are major contributors of churning 

## Data
The data used is the Syria Tel dataset, containing various customer behaviors in the telecommunication industry. It includes account length, international plan,
voice mail plan, number vmail messages, total day, minutes, total day
calls, total day charge, total evening minutes ,total evening calls,
total evening charge, total night minutes, total night calls, total night
charge, total international minutes, total international calls, total
international charge, customer service calls which serves as predictors in the model and churn which is the dependent variable.

## Methodology
The project followed a standard machine learning workflow:
1. Data Loading & Cleaning
2. Exploratory Data Analysis
3. Preprocessing & Feature engineering
4. Model Development & Evaluation-Fitting various models
5. Model Optimization

Key libraries used include Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn, and imblearn.

## Key Findings
Some highlights from the analysis which showed a greater impact on the customer churn rate include:
-• Total Day Minutes
• Total International Minutes
• Total Day Charge
• Total Evening Charge
• Customer Service calls
• International Calls
• Total Charge ()

Random forest model performed best with a higher level of accuracy with highest AUC score

- 

## Repository Contents
- Jupyter Notebook containing full project code and analysis.
- `syriatel` - original dataset.
- `README.md`

