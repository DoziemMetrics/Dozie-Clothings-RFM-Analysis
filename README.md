# Dozie Clothings RFM Analysis

![Dozie Clothings Logo](https://github.com/DoziemMetrics/Dozie-Clothings-RFM-Analysis/blob/main/images.jpeg)

## Overview

Welcome to the Dozie Clothings RFM Analysis repository! This project aims to analyze the customer data of Dozie Clothings, a leading clothing store, using the RFM (Recency, Frequency, Monetary Value) analysis technique. By examining customer behavior and spending patterns, we gain valuable insights to enhance customer engagement and optimize marketing strategies.

## Analysis Steps

The RFM analysis was conducted in several steps:

1. **Data Preparation**: The customer dataset was cleaned, ensuring there were no duplicate entries or missing values. The 'PurchaseDate' column was converted to a datetime data type.

2. **Recency, Frequency, and Monetary Value (RFM) Calculation**: The recency, frequency, and monetary value metrics were calculated for each customer. Recency represents the number of days since the most recent purchase, frequency counts the number of transactions, and monetary value sums the total purchase amount.

3. **Custom RFM Score Assignment**: Instead of quartiles, we customized the RFM score assignment. For recency, we assigned scores based on 30, 90, and 180-day thresholds. For monetary value, we classified customers as high, medium, low, or very low spenders based on custom thresholds.

4. **RFM Score Combination**: The individual recency, frequency, and monetary value scores were combined to calculate the overall RFM score for each customer.

5. **Customer Segmentation**: Customers were segmented into three categories: "High Value," "Medium Value," and "Low Value," based on their RFM scores.

## Key Findings

After analyzing the data, we made the following key observations:

- The best performing month was May 2023, with the highest number of transactions.
- Tokyo was the best-performing location, indicating strong customer engagement.
- Product C was the most performing product, driving significant sales.

## Recommendations

Based on the insights gained from the RFM analysis, we propose the following recommendations:

- Focus on targeted marketing efforts in May 2023 to capitalize on high customer engagement during the best performing month.
- Implement tailored strategies to enhance customer engagement and sales in Paris, the least performing location.
- Leverage the popularity of Product C to strengthen the overall product portfolio and identify factors contributing to its success.

## Further Usage

You are welcome to explore the Python script provided in this repository to delve deeper into the analysis and make improvements based on new data or business requirements. Feel free to customize the RFM score assignment or segment criteria according to the evolving needs of Dozie Clothings.

## Acknowledgements

We extend our gratitude to the team at Dozie Clothings for providing the customer data for this analysis and supporting data-driven decision-making.

