# 💳 Telco Customer Churn Analysis (Python)
A full Python-based data analysis and machine learning project predicting customer churn using the Telco Customer dataset.

## 📊 Key Features
- **KPIs:** Overall Churn Rate, Average Tenure, Average Monthly Charges  
- **EDA:** Churn by Contract Type, Payment Method, Internet Service, Gender, Senior Citizen  
- **Models:** Logistic Regression & Random Forest (ROC-AUC and Accuracy comparison)  
- **Visuals:** Churn Segmentation Charts, Confusion Matrices, ROC Curves, Feature Importance  
- **Deliverables:** Churn Insights Report, Predictive Model, and Business Recommendations  

## 🧹 Data Workflow
- **Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Cleaned using:** Python (pandas, numpy – fixed data types, handled missing `TotalCharges`)  
- **Explored with:** matplotlib, seaborn (visualized churn rate by customer groups)  
- **Modeled with:** scikit-learn (Logistic Regression, Random Forest, Pipeline, Preprocessing)  
- **Evaluated using:** ROC-AUC, Accuracy, Precision, Recall  

## 📈 Insights
- Overall churn rate of **~26%**  
- **Month-to-month contracts** show the highest churn  
- **Higher monthly charges** and **shorter tenure** increase churn likelihood  
- **Fiber optic internet** and **electronic check payments** are strong churn predictors  
- **Paperless billing** slightly increases churn probability  
- Logistic Regression achieved the **highest ROC-AUC (0.841)** and **Accuracy (0.80)**  

## 🧠 Modeling Summary
- **Logistic Regression:** ROC-AUC = 0.841 | Accuracy = 0.801 | Precision = 0.647 | Recall = 0.553  
- **Random Forest:** ROC-AUC = 0.822 | Accuracy = 0.784 | Precision = 0.619 | Recall = 0.487  
- **Top Predictors:** TotalCharges, MonthlyCharges, Tenure, Contract Type, Fiber Optic Internet, Paperless Billing, Electronic Check  

## 💡 Business Recommendations
- Focus retention on **month-to-month customers** early in their lifecycle  
- Offer **loyalty discounts** to high-charge, short-tenure customers  
- Review **pricing & satisfaction** for fiber optic users  
- Use **logistic regression** for deployment — interpretable and ideal for dashboards  

## 🧰 Tools Used
Python · pandas · numpy · matplotlib · seaborn · scikit-learn · Jupyter Notebook  
