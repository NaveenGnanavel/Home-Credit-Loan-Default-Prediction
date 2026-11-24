# Home Credit Loan Default Prediction

## Project Overview
The **Home Credit Loan Default Prediction** project uses Machine Learning techniques to predict the likelihood of a customer defaulting on a loan. The objective is to help financial institutions assess credit risk, understand customer repayment behavior, and support better lending decisions.

## Problem Statement
Financial institutions face challenges in identifying customers who may have difficulty repaying loans. This project analyzes customer financial information and historical credit data to build a predictive model that estimates loan default risk.

## Project Objectives
- Perform Exploratory Data Analysis (EDA) to understand customer financial data.
- Identify important factors influencing loan default.
- Clean and preprocess the dataset.
- Perform feature engineering and data transformation.
- Build and evaluate Machine Learning models.
- Predict customer loan default risk.

## Dataset Description
The project uses the Home Credit Default Risk dataset, which contains customer application details and historical financial information.

The datasets used during development include:
- Application Training Data
- Bureau Credit History
- Bureau Balance
- Previous Applications
- POS Cash Balance
- Credit Card Balance
- Installment Payments

**Note:** Original CSV datasets are not included in this repository.

## Technologies Used
- **Programming Language:** Python
- **Development Environment:** Jupyter Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Model Serialization:** Pickle
- **Version Control:** Git and GitHub

## Project Workflow
1. Data Collection and Understanding
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Building and Training
6. Model Evaluation
7. Model Saving using Pickle

## Repository Structure

```text
Home-Credit-Loan-Default-Prediction/
│
├── HomeLoanDef.ipynb
├── loan_default_prediction_model.pkl
├── README.md
├── requirements.txt
├── .gitignore
└── .gitattributes
```

## Model Deployment / Usage
The trained model is saved as a Pickle file.

Load the model using:

```python
import pickle

with open("loan_default_prediction_model.pkl", "rb") as file:
    model = pickle.load(file)
```

Use the same feature columns, preprocessing steps, and column order used during model training when making predictions.

## Key Outcomes
- Analyzed customer financial and credit-related information.
- Identified patterns associated with loan default risk.
- Developed a Machine Learning model for loan default prediction.
- Saved the trained model for future predictions.

## Future Improvements
- Improve model performance through hyperparameter tuning.
- Explore advanced algorithms such as XGBoost and LightGBM.
- Develop an interactive prediction application using Streamlit.
- Deploy the model as a web-based service.

## Author
**Naveen Gnanavel**

- GitHub: [NaveenGnanavel](https://github.com/NaveenGnanavel)
- LinkedIn: [Naveen Gnanavel](https://www.linkedin.com/in/naveen-gnanavel-a570a1301/)

---

⭐ If you find this project useful, feel free to explore the repository and provide feedback.
