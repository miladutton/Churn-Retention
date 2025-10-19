##💳 Telco Customer Churn Analysis (Python)
A complete Python data analysis and machine learning project predicting customer churn using the Telco Customer dataset.

##📊 Key Features
KPIs: Overall Churn Rate, Average Tenure, Average Monthly Charges
EDA: Churn by Contract Type, Payment Method, Internet Service, Gender, Senior Citizen
Models: Logistic Regression & Random Forest (with ROC-AUC comparison)
Visuals: Feature Importances, Confusion Matrices, ROC & Precision-Recall Curves
Deliverables: Churn Insights Report, Predictive Model, and Actionable Business Recommendations

##🧹 Data Workflow
Source: Telco Customer Churn Dataset
Cleaned in: Python (pandas & numpy — fixed data types, handled missing TotalCharges)
EDA Tools: matplotlib, seaborn (visualized churn rate by customer segments)
Modeling: sklearn (Logistic Regression, Random Forest, Pipeline, Preprocessing)
Evaluation: ROC-AUC, Accuracy, Precision, Recall

##🔍 Insights
Overall churn rate ≈ 26%
Month-to-month contracts show the highest churn
Higher monthly charges and shorter tenure strongly predict churn
Customers using fiber optic internet and paying via electronic check churn more
Paperless billing and male customers slightly more likely to leave
Logistic Regression achieved the highest ROC-AUC (0.841) and Accuracy (0.80)

##🧠 Modeling Summary
Logistic Regression: ROC-AUC = 0.841 | Accuracy = 0.801 | Precision = 0.647 | Recall = 0.553
Random Forest: ROC-AUC = 0.822 | Accuracy = 0.784 | Precision = 0.619 | Recall = 0.487
Top Predictors: TotalCharges, MonthlyCharges, Tenure, Contract Type, Fiber Optic Internet, Paperless Billing, and Electronic Check Payments

##💡 Business Recommendations
Focus retention efforts on month-to-month customers early in their lifecycle
Offer loyalty incentives or discounts for high-charge, short-tenure customers
Review pricing & service satisfaction for fiber optic users
Use the logistic regression model for deployment — interpretable and reliable for BI dashboards

##🧰 Tools Used
Python • pandas • numpy • matplotlib • seaborn • scikit-learn • Jupyter Notebook
