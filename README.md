# Decision-Focused Loan Approval System

## Overview
This project investigates model multiplicity, explainability, and recourse in machine learning systems for financial decision-making using the German Credit dataset.

Multiple machine learning models were trained and compared to study how similarly performing models can still produce different loan approval decisions.

The project further explores explainable AI (XAI) techniques and recourse analysis to improve transparency in high-stakes financial systems.

---

## Objectives
- Build baseline loan approval prediction systems  
- Compare multiple machine learning models  
- Analyze disagreement between models  
- Apply explainable AI techniques  
- Investigate actionable recourse strategies  

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  
- SHAP  
- Jupyter Notebook  

---

## Models Used
- Logistic Regression  
- Random Forest Classifier  

---

## Key Results
- Logistic Regression Accuracy: 70.5%  
- Random Forest Accuracy: 75.0%  
- Model disagreement: 12.5% of cases  

These findings demonstrate **model multiplicity**, where equally performing models produce different decisions for the same inputs.

---

## Explainability (SHAP)
SHAP analysis was used to interpret feature contributions to model predictions.

![SHAP Summary](figures/shap_summary.png)

---

## Feature Importance
Key drivers of loan approval:

- Credit amount  
- Loan duration  
- Checking account status  
- Age  

![Feature Importance](figures/feature_importance.png)

---

## Recourse Analysis
A simple recourse experiment showed how modifying applicant features affects predictions, highlighting the sensitivity of nonlinear models and the need for causal recourse methods.

---

## Future Work
- Fairness-aware ML  
- Counterfactual explanations  
- Causal recourse modeling  
- Robustness across model families (Rashomon sets)  

---

## Dataset
German Credit Dataset  
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

---

## Author
Katso John Obotsang
