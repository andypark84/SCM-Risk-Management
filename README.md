# Delivery Risk Management for Supply Chains

## Abstract
- **Objectvie**: Predicting delivery risks in supply chains is critical for 
ensuring timely and cost-effective operations. This study analyzed key 
features influencing delivery risks, such as shipping mode, order 
status, and order region, to develop robust predictive models. 
- **Results**: Gradient Boosting was identified as the most effective model, 
achieving a 71% accuracy rate. The project emphasized the 
importance of feature engineering, preprocessing, and rigorous 
evaluation in supply chain analytics.

---
## Analysis Questions
In this Supply Chain Analysis, the following key questions are addressed:

1) **How do different customer segments and demographics influence profitability and sales volume?**
   - By examining customer segments (e.g., region, demographics), high-value segments are identified to tailor marketing strategies and optimize resource allocation based on profitability potential.

2) **Which predictive model performs best in predicting late delivery risk?**
   - This analysis evaluates multiple predictive models to determine the model with the highest accuracy for predicting late delivery risks. The best-performing model ensures reliable predictions, aiding logistics planning and operations.

3) **What are the most significant factors contributing to late delivery risk?**
   - By identifying key factors driving delivery risks, this analysis provides insights for targeted improvements in shipping processes to reduce delays and enhance overall supply chain efficiency.

---
##  Dataset and Methods
1) Dataset (Dimension 180519 rows x 53 features) 
 • Features analyzed: Shipping mode, order status, order region, and 
order quantity
 • Target variable: Delivery risk (binary classification: high vs. low risk)
2) Preprocessing
 • Consolidation of low-frequency categories to improve model robustness. Among the categorical variables, category name(category_name) and department name(department_name) exhibited the highest number of unique values, making them critical for this preprocessing. 
 • Scaling of numerical features using Standard Scaling normalization.

---
##  Methodology
1) Pearson Correlation: Pearson correlation analysis was conducted to identify highly correlated variables. Features with strong correlations were carefully examined, and redundant variables were removed to address multicollinearity and enhance model performance.
2) Machine Learning Models: The machine learning models utilized in this project include Gradient Boosting, AdaBoost, XGBoost, Logistic Regression, Naive Bayes, Random Forest, Decision Tree, K-Nearest Neighbors (KNN).
---
## Results
1) Model Comparison:
   - Gradient Boosting achieved the highest accuracy of 71%.
   - KNN and Naive Bayes underperformed due to limited adaptability to non-linear relationships in the data.

2) Feature Importance:
   - 'Shipping mode' and 'order status' were the most critical predictors, contributing significantly to model performance.

3) Final Model: Gradient Boosting
   - Accuracy: 71%
   - Precision: 76%
   - Recall: 71%
   - F1 Score: 70%

