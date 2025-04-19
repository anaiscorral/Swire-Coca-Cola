# Overview
This project focuses on analyzing customer segmentation and optimizing delivery costs for Swire Coca-Cola. The goal is to improve customer engagement, reduce delivery costs, and identify opportunities for growth in high-volume customers.

## Business Problem:
Optimizing logistics by identifying high-potential customers currently on white truck (ARTM) delivery and shifting them to red truck (direct delivery) to support future growth while maintaining cost efficiency.

# Steps & Contributions to the Project
My personal contributions to the project are outlined in the following files in the repo:

- EDA (Exploratory Data Analysis): Conducted initial data exploration, identifying trends and insights in customer data.

- XGBoost Analysis: Developed and analyzed an XGBoost model to classify customers into growth categories.

- XGBoost Segmentation: Implemented customer segmentation based on the XGBoost model results.

- Group Project Presentation: Designed and laid out the final presentation for the group.

# Technologies Used
R Programming

# Key Findings
### 1) High-Growth Customers: 
The analysis identified key characteristics of high-growth customers. These include:

- Top Channel: Dining (specifically in restaurants or related locations)

- Top Trade Channel: Fast Casual Dining

- Top Frequent Order Type: Sales Rep

- Top State: Massachusetts

- Average Delivery Cost: $2.88 per delivery

These insights are valuable because they help Swire Coca-Cola pinpoint high-growth customers, allowing them to tailor marketing and sales strategies for this segment. By understanding which channels and order types are most commonly used, Swire can focus on these characteristics to optimize delivery and marketing efforts, specifically targeting customers who are most likely to convert to direct red truck delivery.

### 2) XGBoost Segmentation: 
The segmentation analysis was performed using XGBoost, a machine learning model, to predict customer behavior based on historical data. Delivered Cases was chosen as the target variable instead of Delivered Gallons because XGBoost showed a better performance, reducing the RMSE from 17 to 11. This improvement in model accuracy ensures that Swire Coca-Cola can more confidently identify high-potential customers for red truck delivery and better understand their logistics needs.





