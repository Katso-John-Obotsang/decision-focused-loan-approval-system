\# Decision-Focused Loan Approval System



\## Overview



This project investigates model multiplicity, explainability, and recourse in machine learning systems for financial decision-making.



Using the German Credit dataset, multiple machine learning models were trained and compared to study how similarly performing models can produce different loan approval decisions.



The project further explores explainable AI techniques and simple recourse analysis to improve transparency in high-stakes financial systems.



\---



\## Objectives



\- Build baseline loan approval prediction systems

\- Compare multiple machine learning models

\- Analyze disagreement between models

\- Explore explainable AI techniques

\- Investigate actionable recourse strategies



\---



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Matplotlib

\- SHAP

\- Jupyter Notebook



\---



\## Project Structure



```text

Decision-Focused-Loan-Approval-System/

│

├── data/

├── figures/

├── notebooks/

├── results/

├── src/

├── README.md

└── requirements.txt

```



\---



\## Models Used



\- Logistic Regression

\- Random Forest Classifier



\---



\## Key Results



\- Logistic Regression Accuracy: 70.5%

\- Random Forest Accuracy: 75.0%

\- Model disagreement observed in 12.5% of cases



These results demonstrate the phenomenon of model multiplicity, where similarly performing models produce different decisions for the same applicants.



\---



\## Feature Importance Analysis



The Random Forest model identified financial variables such as:



\- Credit amount

\- Loan duration

\- Checking account status

\- Age



as major drivers of loan approval decisions.



\### Feature Importance Plot



!\[Feature Importance](figures/feature\_importance.png)



\---



\## SHAP Explainability Analysis



SHAP values were used to examine how individual features influence model predictions and approval outcomes.



\### SHAP Summary Plot



!\[SHAP Summary](figures/shap\_summary.png)



\---



\## Recourse Experiment



A simple recourse experiment was conducted by modifying applicant financial variables and re-evaluating approval probabilities.



The results demonstrated that nonlinear machine learning systems may respond unexpectedly to isolated feature changes, motivating the need for causal recourse methods.



\---



\## Future Work



\- Fairness-aware machine learning

\- Causal recourse analysis

\- Counterfactual explanations

\- Decision-focused learning

\- Robustness analysis across Rashomon sets



\---



\## Dataset



German Credit Dataset:

https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)



\---



\## Author



Katso John Obotsang

