# Overview
This project focuses on analyzing customer segmentation and optimizing delivery costs for Swire Coca-Cola. The goal is to improve customer engagement, reduce delivery costs, and identify opportunities for growth in high-volume customers.

## Business Problem:
Optimizing logistics by identifying high-potential customers currently on white truck (ARTM) delivery and shifting them to red truck (direct delivery) to support future growth while maintaining cost efficiency.

# Steps & Contributions to the Project
My personal contributions to the project are outlined in the following files in the repo:

- EDA (Exploratory Data Analysis): Conducted initial data exploration, identifying trends and insights in customer data.
- XGBoost Analysis: Developed and analyzed an XGBoost model to classify customers into growth categories.
- XGBoost Segmentation: Implemented customer segmentation based on the XGBoost model results.
- Strategy and estimated profit and revenue impact. Converting 5% of Sales Rep customers could add $130M in revenue and $39M in profit annually.
- Group Project Presentation: Designed and laid out the final presentation for the group.

# Technologies Used
R Programming

# Key Findings

### 1) XGBoost Segmentation: 
The segmentation analysis was performed using XGBoost, a machine learning model, to predict customer behavior based on historical data. Delivered Cases was chosen as the target variable instead of Delivered Gallons because XGBoost showed a better performance, reducing the RMSE from 17 to 11. This improvement in model accuracy ensures that Swire Coca-Cola can more confidently identify high-potential customers for red truck delivery and better understand their logistics needs.

**Distribution of customer segmentation, based on low, medium, and high growth customer prediction.**
![EDA and Modeling](https://github.com/anaiscorral/Swire-Coca-Cola/blob/main/EDA%20and%20modeling.png)

### 2) High-Growth Customers: 
The analysis identified key characteristics of high-growth customers. These include:

- Top Channel: Dining (specifically in restaurants or related locations)
- Top Trade Channel: Fast Casual Dining
- Top Frequent Order Type: Sales Rep
- Top State: Massachusetts
- Average Delivery Cost: $2.88 per delivery

These insights are valuable because they help Swire Coca-Cola pinpoint high-growth customers, allowing them to tailor marketing and sales strategies for this segment. By understanding which channels and order types are most commonly used, Swire can focus on these characteristics to optimize delivery and marketing efforts, specifically targeting customers who are most likely to convert to direct red truck delivery.

![Findings](https://github.com/anaiscorral/Swire-Coca-Cola/blob/main/Findings.png)
![Findings2](https://github.com/anaiscorral/Swire-Coca-Cola/blob/main/Findings2.png)
![Findings3](https://github.com/anaiscorral/Swire-Coca-Cola/blob/main/Findings3.png)

## The Business Value of the Solution:
**Optimize Delivery Routes:**

- Reduce costs by re-planning routes and offering bulk discounts.
- Shift to off-peak hours for deliveries.

**Strengthen Sales Rep Engagement:**

- Empower sales reps with tools for growth and personalized offers.
- Introduce performance-based incentives to increase customer loyalty and conversion.

**Potential Revenue Impact:**

- Converting 5% of Sales Rep customers could add $130M in revenue and $39M in profit annually.
These strategies focus on cost efficiency and leveraging sales reps to drive growth.

## Difficulties my Group Encountered Along the Way:
- Aligning training and test datasets due to inconsistent column structures and factor levels.
- Addressing missing values and high-dimensional data with extensive preprocessing.
- Interpreting RMSE and other metrics for business-friendly communication.

## What I Learned in the Project:
- Handling complex datasets with an unknown target variable and a broad scope.
- Comparing and interpreting machine learning models using business-relevant metrics.
- Translating technical findings into actionable recommendations for stakeholders.








