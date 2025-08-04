# Customer Churn Analysis of Telecommunication Services data using SQL and PowerBI

## Table of content
- [Project Overview](##Project-Overview)
- [Data Set](##Data-Set)
- [Tech Stack](##Tech=Stack)
- [Highlights](##Highlights)
- [Walkthrough of Visuals with Insights](##Walkthrough-of-Visuals-with-Insights)
- [Business Impact & Insights](##Business-Impact-&-Insights)
- [Dashboard Demo:](###Dashboard-Demo)

## Project Overview
The Customer Churn Analysis Dashboard provides deep insights into customer attrition patterns by visualizing demographics, service usage, contracts, reasons  and payment behavior. Designed to help the user to  identify high-risk segments and improve proactive retention strategies. <br> <br>

## Data Set
**Customer data of a telecom service provider.**

- The data includes 3,200 customer records covering:

- Demographics (gender, age group, region)

- Service features (internet, TV, security, premium support, etc.)

- Payment methods

- Contract types and tenure

- Churn status and category (reason for leaving)<br> <br>

## Tech Stack
**The dashboard was built using the following tools and technologies:**

- SQL - Used to prepare supporting data tables from main data table

- Power Query - Used for data cleaning and transformation before visualization

- DAX - Used to developed custom KPIs and dynamic measures for churn rates and segmentation

- Power BI Desktop - Primary platform for data visualization and report creation

- Data Modeling - Created relationships between customer attributes, service usage, and churn indicators for cross-filtering and aggregation

- File Format - .pbix (Power BI) and .png for image previews <br> <br>

## Highlights

### • Business Problem

Telecom and internet service providers often face high customer churn, impacting revenue and growth. Understanding **who** is leaving and **why** is critical to building targeted retention strategies.

### • Goal of the Dashboard

To develop a visually intuitive and actionable dashboard that:

- Identifies key churn drivers across customer segments  
- Monitors overall churn performance  
- Enables decision-makers to design personalized retention interventions  
- Tracks churn distribution by product, payment method, and contract  

## Walkthrough of Visuals with Insights

- **Top KPIs:**  
  - Total Customers: 3,195  
  - New Joiners: 200  
  - Total Churn: 849  
  - Churn Rate: **26.57%** (It is concerning) 

- **Churn by Gender:**  
  - Slightly higher churn observed in **male customers (27.01%)** vs. females (25.85%)

- **Churn by State:**  
  - Highest churn in **Jammu & Kashmir**, followed by **Assam** and **Delhi**

- **Churn by Contract Type:**  
  - **Month-to-month** contracts had the highest churn rate, indicating the risk in short-term agreements

- **Churn by Payment Method:**  
  - Customers using **Mailed Checks** or **Bank Withdrawals** churned more frequently than **Credit Card** users

- **Churn by Internet Type:**  
  - **Fiber optic users** exhibited the highest churn.

- **Churn Category Breakdown:**  
  - Major reasons: **Competition**, **Dissatisfaction**, and **Service & Support Person's Attitude**, **Price**
  - Among the above reasons, most of the churn is observed due to the **Competitors Better Offer and Services**

- **Churn by Tenure & Age Groups:**  
  - Customers aged **>50** and those with **<12 months** of tenure were more likely to churn

- **Service-Wise Churn Table:**  
  - Highest churn observed among customers **without backup, security, or device protection**  having services **Internet Service, Phone Service, Unlimited Data and Paperless Billing**
  - Services like **Premium Support**, **Online Security**, and **Streaming TV** strongly correlated with lower churn <br> <br>

## Business Impact & Insights

 To reduce customer churn, the business should focus on converting month-to-month contract users into long-term plans by offering discounts and added benefits. Encouraging digital payment methods like credit cards or UPI through incentives can also help retain customers, as mailed checks and bank withdrawals show higher churn. Since many customers leave due to better competitor offers and dissatisfaction, it's essential to introduce competitive pricing bundles, improve support quality through training, and offer loyalty rewards. Special attention should be given to high-risk segments, new customers and those over 50 by providing onboarding support and simplified services. Lastly, promoting value-added service bundles such as security, backup, and premium support can increase stickiness and reduce churn among service-heavy users.


### Dashboard Demo
<img width="1456" height="846" alt="PNG-Customer-Churn-Analysis" src="https://github.com/user-attachments/assets/12b8eddf-495f-4099-bd9f-3cecfb228dfc" />




