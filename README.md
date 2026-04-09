# Telecom Customer Churn Analysis

## Overview
This project analyses customer churn in a telecommunications company to identify key drivers and build predictive models that detect at-risk customers.

## Business Objectives
The primary goal is to support the telecom company in reducing its **26.5% churn rate**, which currently exceeds the industry benchmark. Key objectives include:
* **Exploratory Data Analysis (EDA):** Identify key factors influencing churn.
* **Churn Prediction:** Develop machine learning models to detect high-risk customers.
* **Strategic Recommendations:** Propose data-driven retention strategies to improve profitability.

## Methodology
Customer churn was analysed using **Python**, combining data cleaning, exploratory analysis, and machine learning. Predictive models were used to identify at-risk customers, while clustering techniques enabled customer segmentation for targeted retention strategies.

## Key Insights
The telecom company is experiencing a **high churn rate (26.5%)**, exceeding the industry benchmark (15–22%).

![Image 1]([path/to/your/image1.png](https://github.com/zoeyydao/Telco-Customer-Churn-Project/blob/7e0b58b190fc0bd9ab2ceb437a384abe1320a9ed/images/churn%20percentage.png))

The analysis revealed several critical determinants of churn:

* **Demographics:** Senior citizens churn at 41.7% (nearly double the rate of younger demographics). Additionally, customers without partners or dependents show a higher propensity to leave.

![Image 2](path/to/your/image2.png)
![Image 3](path/to/your/image3.png)

* **Customer Tenure:** New customers (0-12 months) exhibit a 47.7% churn rate, indicating a need for better early-stage engagement.

![Image 4](path/to/your/image4.png)

* **Internet Service:** Fiber-optic users are significantly more prone to churn (41.9%) compared to DSL users. This suggests high price sensitivity or dissatisfaction with premium-tier pricing.

![Image 5](path/to/your/image5.png)

* **Contract Type:** Customers on month-to-month contracts have the highest churn rate (42.7%), whereas two-year contracts offer the most stability (2.85%).

![Image 6](path/to/your/image6.png)

* **Monthly Charges Distribution:** High-paying customers churn more, further confirming that price sensitivity is a primary driver.

![Image 7](path/to/your/image7.png)

* **Payment and Billing Behavior:** Electronic check payments and paperless billing are strongly associated with increased churn.

![Image 8](path/to/your/image8.png)
![Image 9](path/to/your/image9.png)

## Methodology & Models
Several predictive models were developed and evaluated, including **Logistic Regression, Decision Tree, Random Forest, and XGBoost**.

![Image 10](path/to/your/image10.png)

* **Top Performer:** The **tuned Random Forest model** was identified as the most suitable for operational use due to its balance of accuracy and business efficiency.

![Image 11](path/to/your/image11.png)

* **Feature Importance:** Top predictors are Tenure, Total Charges, Internet Service, Contract and Payment Method.

![Image 12](path/to/your/image12.png)

* **Segmentation:** K-means clustering was used to create risk-based customer groups for targeted outreach.

![Image 13](path/to/your/image13.png)

## Recommendations
* Implement a multi-layered retention strategy focusing on early-stage onboarding for new customers.
* Encourage shifts toward long-term contracts and automatic payment methods.
* Improve fiber service quality and transparency regarding high-cost plan pricing.
* Develop a model-driven early warning system for proactive customer engagement.
