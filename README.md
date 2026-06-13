# Customer-Churn-Prediction
A machine learning project that predicts customer churn using classification models such as Logistic Regression, Decision Trees, and Random Forest, with model evaluation and hyperparameter tuning for performance optimization.


##  Overview

This project focuses on predicting customer churn using a structured dataset containing customer usage and service information. The goal was to build classification models that can accurately identify customers who are likely to stop using the service.

By applying different machine learning models, the project highlights how data-driven approaches can support decision-making in customer retention.



##  About the Dataset

The dataset contains telecom customer data with features such as:

- Customer account information (state, account length)  
- Service details (international plan, voicemail plan)  
- Usage metrics (day, evening, night, and international minutes)  
- Charges and number of calls  
- Customer service interactions  
- Target variable: **Churn (whether the customer left or not)**  

The dataset was split into training (80%) and testing (20%) sets for model evaluation.   



##  Analysis Approach

###  Data Preparation

The dataset was cleaned and transformed to prepare it for machine learning models:

- Converting categorical values (Yes/No) into numerical format  
- Encoding categorical features such as state using label encoding  
- Splitting data into features and target variable  
- Standardizing numerical values using feature scaling  

These steps ensured the data was suitable for model training.



###  Model Development

Multiple classification models were trained and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  

Each model was evaluated to understand how well it predicts customer churn.

---

###  Model Evaluation

The models were evaluated using key performance metrics:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

These metrics provide a more complete understanding of model performance, especially for classification problems like churn prediction.

---

###  Hyperparameter Tuning

To improve performance, hyperparameter tuning was applied to the Random Forest model using grid search.

Different combinations of parameters (such as number of trees and depth) were tested to find the best configuration.

---

##  Key Insights

From the analysis and model evaluation:

-  Logistic Regression achieved good accuracy but failed to detect many churn cases (low recall)  
-  Decision Tree improved performance with a better balance between precision and recall  
-  Random Forest achieved the best overall performance with the highest accuracy and F1 score  
-  Ensemble methods (like Random Forest) are more effective for this dataset  
-  Hyperparameter tuning did not significantly improve the already strong Random Forest model  

---

##  Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  


##  Conclusion

This project demonstrates how machine learning can be used to predict customer churn and support business decisions.

It highlights:

- The importance of data preprocessing for model performance  
- The differences between classification algorithms  
- The value of evaluation metrics beyond accuracy  
- The effectiveness of ensemble models in prediction tasks  

The project provides a strong foundation for building real-world predictive systems in customer analytics.
  
