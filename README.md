# Customer-Churn-EDA-Prediction---Python-ML
Welcome to the Customer Churn Analysis project repository! This project aims to explore customer churn patterns in a telecommunications company and build predictive models to anticipate customer attrition. By analyzing historical data and identifying key factors influencing churn, we strive to provide insights and actionable recommendations to mitigate churn and enhance customer retention strategies.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
The primary objective of this project is to:
- Explore customer churn patterns and identify factors contributing to customer attrition.
- Build predictive models using machine learning algorithms to forecast customer churn.
- Evaluate model performance and derive actionable insights to inform retention strategies.

## Data Source
The dataset used in this analysis is sourced from 10Alytics, containing information on telecom customers, including demographic details, service subscriptions, billing information, and churn status. The dataset comprises  7043 observations and  21 features.

## Data Processing
- Data cleaning: Preprocess the dataset by handling missing values, balancing the dataset, encoding categorical variables, and standardizing numerical features.
- Exploratory Data Analysis (EDA): Conduct comprehensive EDA to understand the distribution of features, analyze correlations, and identify patterns related to churn.
- Feature Engineering: Derive new features or transformations to improve model performance.

## Evaluation Metrices
The performance of predictive models is evaluated using the following metrics:
- Accuracy: Measures the proportion of correctly classified instances.
- F1 Score: Harmonic mean of precision and recall, providing a balance between false positives and false negatives.
- ROC AUC Score: Indicates the model's ability to distinguish between positive and negative classes.
- Confusion Matrix: Visual representation of model predictions compared to actual outcomes.

## key Insights
1. Customer Demographics
- Males are slightly more prevalent (50.48%) than females.
- A majority (51.7%) have no partners and 70% have no dependents.
2. Service Usage
- High phone service penetration (90%) with a preference for multiple lines (58%).
- Lower adoption of internet services (44%).
- Low usage of protection/security services (online security: 29%, device protection: 34%, tech support: 29%, online backup: 39%).
- Streaming services have moderate adoption (TV: 39%, Movies: 39%).
3. Contract & Payment
- Majority use paperless billing (59%) but prefer credit cards (41%) over electronic checks (unknown %).
- Month-to-month contracts are more popular (55%) compared to longer terms.
- Customers value convenience (paperless billing) and flexibility (month-to-month contracts).
4. Churn Impact
- Churn rate is 27%.
- Revenue loss due to churn is 17.83%.
- Churned customers have lower average revenue than retained customers.
5. Feature Importance
- TotalCharges, MonthlyCharges, tenure, contract type, and payment method emerge as the top five features influencing churn.
- Tenure, monthly charges, and total charges are key churn predictors (shorter tenure, higher monthly charges, lower total charges correlate with churn).
6. Other Observations:
- No significant churn difference based on gender.
- Customers with partners and dependents churn less.
- Churn is higher for customers with phone service, online security, online backup, but lower for those without device protection, tech support, or streaming services.
- Paperless billing and electronic check payments correlate with higher churn, while credit cards correlate with lower churn.
- Notably, customers with fiber optic internet and those without online security or tech support exhibit higher churn rates.
- Non-senior citizens churn more.
- Customers with month-to-month subscriptions have a higher churn proportion while those with two year subscriptions have lower churn proportion.
7. Model Comparism and Building
- In a customer churn prediction project, focusing on false negatives (missed churn) is generally more important than false positives (incorrectly predicting churn).
- Optimized GBC Model gave the lowest false negative of 98, and a high accuracy score of 78%
  
## Conclusion and Recommendations
1. Targeted Bundling:
- Offer bundled packages that combine high phone service penetration (multiple lines) with high-value internet options.
- Consider including basic online security features in these bundles to address low adoption rates and potentially increase perceived value.

2. Security & Support Package:
- Develop a comprehensive security & support package that combines online security, device protection, tech support, and online backup.
- Offer this package at a discounted rate compared to purchasing services individually to incentivize adoption and address low usage rates.

3. Flexible Payment Options with Incentives:
- While customers value convenience (paperless billing), explore offering incentives for automatic payments via credit card (lowest churn rate) to encourage on-time payments and potentially reduce churn.
- Highlight the benefits of longer contracts (incentives, discounts, stability) through targeted communication for customers on month-to-month plans.

4. Customer Segmentation and Retention Programs:
- Implement customer segmentation based on churn risk factors (tenure, monthly charges, service usage).
- Develop targeted retention programs for high-risk customer segments. These programs could include:
- Personalized communication highlighting the value they receive from the service.
- Exclusive discounts or promotions to incentivize continued service.
- Proactive outreach to address potential issues and improve customer satisfaction.

5. Targeted Churn Prevention Strategies:
- Develop targeted campaigns based on customer profiles and service usage.
- For customers with partners and dependents (lower churn), focus on communication that emphasizes family-oriented benefits of the service.
- For customers with higher churn despite using phone and internet services, investigate reasons for dissatisfaction and offer targeted solutions (e.g., improve customer service experience, address specific service issues).
- Develop win-back campaigns for high-value customers who churn (lower total charges but potentially high tenure) with attractive incentives to rejoin.
