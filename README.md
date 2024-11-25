# SCM-Risk-Management

## Dataset
The analysis is based on the **DataCo Supply Chain Dataset**, a simulated dataset commonly used for supply chain analysis. 

## Analysis Questions
This project aims to address the following key questions:

1. **How do customer segments influence profitability and sales volume?**
   - By analyzing customer demographics, we can identify high-value segments for targeted strategies.
   
2. **Which predictive model performs best in predicting late delivery risks?**
   - Various machine learning models are tested to find the most accurate predictor.

3. **What are the key factors contributing to late delivery risks?**
   - Feature importance analysis highlights significant drivers of late deliveries.
## Key Features for Delivery Risk Prediction

The following features were selected for delivery risk prediction based on their relevance and impact:

1. **Days for shipping (real)** & **Days for shipment (scheduled)**:
   - The difference between the actual and scheduled shipping days directly impacts the likelihood of delays.

2. **Benefit per order**:
   - High profit per order may influence business priorities, as higher-value orders could be prioritized for faster processing, potentially affecting delivery risk.

3. **Sales per customer**:
   - Total sales per customer indicate customer value and repeat purchase frequency. Important or high-value customers may receive priority, affecting delivery timelines.

4. **Delivery Status**:
   - The previous delivery status offers insights into historical delivery patterns, providing valuable information to predict potential delays.

5. **Late_delivery_risk**:
   - Existing risk flags from previous orders help the model recognize recurring delay patterns, making it easier to identify orders at risk of delay.

6. **Order Item Discount Rate**:
   - High discount rates might reduce the priority of certain orders, potentially increasing delivery time and influencing risk.

7. **Order Item Quantity**:
   - Larger order quantities may require additional handling and preparation time, which could increase the chance of delays.

8. **Order Profit Per Order**:
   - Similar to benefit per order, per-order profit could affect prioritization, as high-profit items are more likely to be expedited, reducing delay risks.

9. **Order Region** & **Market**:
   - The location of the order and market can reflect logistical complexities. Certain regions might be more susceptible to delays due to distance, regulations, or infrastructure.

10. **Shipping Mode**:
    - The chosen shipping mode (e.g., standard, expedited) has a direct impact on expected delivery time and delay likelihood. Express shipping modes tend to have lower delay risks.

11. **Product Category Id** & **Department Name**:
    - Certain categories or departments might have different processing requirements, affecting delivery speed. For example, fragile or high-demand items may require specialized handling, impacting delivery timelines.

12. **Order Item Product Price**:
    - High product prices may lead to prioritized handling, as businesses might be inclined to prioritize valuable items to maintain customer satisfaction.
