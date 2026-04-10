# 🛒 customer-purchase-prediction & business-insights-dashboard

## Project Overview
This project focuses on predicting whether a customer will complete a purchase based on browsing behavior and session data.

It combines:
- Machine Learning for prediction
- Power BI for business intelligence and visualization
The goal is to help businesses improve conversion rates, optimize marketing strategies, and better understand customer behavior.

##  Problem Statement
E-commerce platforms experience a high volume of visitors, but only a small percentage convert into buyers. Identifying which users are likely to make a purchase is critical for improving marketing efficiency and increasing revenue.
This project develops a classification model to predict customer purchase intent using behavioral and session-based data.

##  Business Importance
- Improve targeted marketing campaigns  
- Increase conversion rates  
- Reduce unnecessary advertising spend  
- Enable personalized user experiences  
- Support data-driven decision making  

##  Dataset
Online Shoppers Purchasing Intention Dataset  
https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset

##  Exploratory Data Analysis
Key steps:
- Analyzed customer browsing patterns  
- Identified relationships between engagement metrics and purchases  
- Detected class imbalance in the target variable  

##  Modeling Approach
The following models were implemented:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  

##  Evaluation Metric
F1-score was used as the primary evaluation metric due to class imbalance, ensuring a balance between precision and recall.

##  Key Modeling Decision
Although the dataset was imbalanced, SMOTE was not applied to preserve real-world customer behavior.
Instead, model performance was evaluated using F1-score for a more reliable assessment.

##  Key Insights
- Customers with higher PageValues are more likely to make a purchase  
- High BounceRates negatively impact conversion  
- Returning visitors have a higher probability of purchasing  
- Purchase probability helps identify high-intent customers  

## Power BI Dashboard
The dashboard translates model outputs into business insights, enabling decision-makers to:
- Monitor conversion rates  
- Identify high-intent customers  
- Analyze behavioral patterns  
- Compare predicted vs actual outcomes

- ### 📸 Dashboard Preview
<img width="779" height="442" alt="power dashboard" src="https://github.com/user-attachments/assets/204d28de-7a57-4515-bdd4-33eb497974fe" />

##  Dashboard Features
- KPI Metrics (Conversion Rate, Total Purchases, Sessions)  
- Customer Behavior Analysis (Bounce Rate, Page Value)  
- Prediction Insights (Purchase Probability)  
- High-Intent Customer Segmentation  
- Interactive Filters (Visitor Type, Month, Weekend)  

##  Project Workflow
1. Data Cleaning & Preparation  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training & Evaluation  
5. Prediction Generation  
6. Power BI Dashboard Development  

## Tools & Technologies
- Python  
- Pandas & NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib & Seaborn  
- Power BI  

##   Business Recommendations
 -Focus marketing efforts on high-intent users 
- Reduce bounce rates through better UX design 
- Target returning visitors with personalized offers 
- Use real-time predictions for dynamic promotions 

## 👤 Author
**Musa Mamman**  
Data Analyst | Aspiring Data Scientist  


