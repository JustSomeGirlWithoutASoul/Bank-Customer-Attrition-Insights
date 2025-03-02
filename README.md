**Bank Customer Attrition Classification**

**Main Objective**

To use different machine learning techniques to predict and analyze bank customer churn. 

By identifying key factors contributing to customer attrition, banks can develop targeted retention strategies and make further tangible stratigies. Therefore, the focus on the model is to predict the user that leave the bank. The main masure therefore is the recall score

**Dataset**

"Bank-Customer-Attrition-Insights-Data.csv" with 10,000 records and 18 features including demographics, account details, engagement metrics, and financial information.

Link to the dataset: https://www.kaggle.com/datasets/marusagar/bank-customer-attrition-insights

**Project Structure**

1. Problem Define
2. Data Insights & EDA
3. Data Preparation
4. Prediction Modeling
   - Base models: Random Forest, XGboosting, Support Vector Machine, Logistic regression (Baseline to compare)
   - Meta Model- Stack Model with Random Forest, XGboosting and Support Vector Machine
6. Causal Infernece 
7. Model Performance & Results
8. Conclusion

**Project Conclusion**

The Meta model with Stacking model increase the recall in 4% from the base models for the interest variable of attrition

High-balance customers are more financially aware and expect premium service—they leave when finding better options.

Older customers tend to stay due to bank loyalty or to avoid time-consuming paperwork.

Regional differences significantly impact churn, suggesting region-specific strategies are needed rather than one-size-fits-all approaches.
