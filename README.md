# Delivery Risk Management for Supply Chains

## Overview
This project analyzes supply chain delivery risks using data-driven approaches and machine learning models. By exploring customer demographics, shipping logistics, and profitability, the analysis aims to identify late delivery risk factors and enhance supply chain efficiency.

---

## Dataset
The analysis is based on the **DataCo Supply Chain Dataset**, a simulated dataset commonly used for supply chain analysis.

## Analysis Questions
In this Supply Chain Analysis, the following key questions are addressed:

1. **How do different customer segments and demographics influence profitability and sales volume?**
   - By examining customer segments (e.g., region, demographics), high-value segments are identified to tailor marketing strategies and optimize resource allocation based on profitability potential.

2. **Which predictive model performs best in predicting late delivery risk?**
   - This analysis evaluates multiple predictive models to determine the model with the highest accuracy for predicting late delivery risks. The best-performing model ensures reliable predictions, aiding logistics planning and operations.

3. **What are the most significant factors contributing to late delivery risk?**
   - By identifying key factors driving delivery risks, this analysis provides insights for targeted improvements in shipping processes to reduce delays and enhance overall supply chain efficiency.

---

## Key Features for Delivery Risk Prediction
The following features were selected based on their relevance and impact on delivery risks:

1. **Days for shipping (real)** & **Days for shipment (scheduled)**:
   - The difference between actual and scheduled shipping days directly impacts delivery delays.

2. **Benefit per order**:
   - High profit per order may influence prioritization, as higher-value orders are often expedited, potentially reducing delay risks.

3. **Sales per customer**:
   - Indicates customer value and repeat purchase frequency. High-value customers may receive priority, affecting delivery timelines.

4. **Delivery Status**:
   - Historical delivery patterns help predict future delivery delays.

5. **Late_delivery_risk**:
   - Previous risk flags allow the model to recognize recurring patterns of delays.

6. **Order Item Discount Rate**:
   - High discounts might deprioritize certain orders, increasing delivery times.

7. **Order Item Quantity**:
   - Larger quantities may require additional handling, which can increase delays.

8. **Order Region** & **Market**:
   - Location-related logistical complexities can impact delivery time.

9. **Shipping Mode**:
   - Express shipping modes typically reduce delays compared to standard modes.

10. **Product Category Id** & **Department Name**:
    - Specific categories or departments may require special handling, affecting delivery speed.

---

## Project Highlights
1. **Preprocessing**:
   - Dropping unnecessary columns
   - Consolidating Low-Frequency Categories into 'Other'
     
2. **Exploratory Data Analysis (EDA)**:
   - Visualized customer demographics and shipping patterns.
   - Identified correlations between delivery delays and order attributes.

3. **Machine Learning Models**:
   - Built and evaluated models including Gradient Boosting, AdaBoost, XGBoost, Logistic Regression, Naive Bayes, Random Forest, Decision Tree, and KNN.
   - Compared model performances to select the best predictor of late delivery risks.


