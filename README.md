# Churnlytics 

**A machine learning-powered telecom churn prediction system .**
Churnlytics—a savior for telecom industries where customer churn threatens profits. In today's scenario, acquisition costs are much higher than retention, making it crucial to predict churn early. Built on the Kaggle Telco dataset, it predicts whether a customer is likely to churn or stay, enabling businesses to act before it’s too late. Because in this game, retaining customers isn’t just strategy , it’s survival.

## Overview  
Churnlytics predicts whether a telecom customer will churn based on factors like **tenure, monthly charges, contract type, online security, and more**. It leverages **Exploratory Data Analysis (EDA)** and a **Decision Tree Classifier** for accurate and interpretable predictions. Since **acquisition costs exceed retention**, this project helps businesses minimize customer churn.


## Dataset  
- **Source:** [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Features Used:**  
  - Demographics (Gender, Senior Citizen, Partner, Dependents)  
  - Account Details (Tenure, Contract, Billing Method)  
  - Services Used (Phone, Internet, Streaming, Security)  
  - Financials (Monthly Charges, Total Charges)  
  - **Target Variable:** Churn (Yes/No)  

##  Tech Stack  
- **Backend:** Flask  
- **Frontend:** HTML, CSS  
- **Machine Learning:** Scikit-learn, Pandas, NumPy, Matplotlib  

##  Features  
✔ **Interactive UI** for user input (Flask-based)  
✔ **Real-time churn prediction** using trained ML model  
✔ **Feature importance analysis** to explain predictions  
✔ **Customizable and scalable** for real-world telecom businesses  

## Installation & Usage  
1. Clone the repository  

  [https://github.com/geekyme-dev/Churn_Predictor]
  
   cd Churnlytics 
   ```  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the application  
   ```bash
   python app.py
   ```  
4. Open in browser: `http://127.0.0.1:5000`  

## Click Here to Watch
![Watch Churnlytics ](https://github.com/user-attachments/assets/7b455c33-6a08-48df-a027-f042abb59e17)


## Model Performance  
- **Algorithm Used:** Decision Tree Classifier  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score  
- **Feature Importance:** Contract type, tenure, monthly charges are key indicators of churn  

## Future Improvements  
- Implement advanced models like **Random Forest, XGBoost** for better accuracy  
- Add **SHAP values** for deeper model interpretability  
- Deploy on **Heroku/Render** for public access  

##  Contribution  
Feel free to fork the repo, raise issues, and submit pull requests.  
