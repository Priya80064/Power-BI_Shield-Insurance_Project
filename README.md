# SHIELD INSURANCE PROJECT

## Project Overview
This project is part of the virtual internship at AtliQ Technologies. The task was to assist Shield Insurance in making data-driven decisions by analyzing their data from November 2022 to April 2023.

## Company Overview
Shield Insurance is an insurance provider operating across five major cities in India: Mumbai, Delhi NCR, Chennai, Hyderabad, and Indore. They offer nine different policies and utilize various sales channels to reach customers, including:

- Offline Agent
- Offline Direct
- Online App
- Online Website

## Dashboard & Presentation Links
- **Dashboard:** https://app.powerbi.com/view?r=eyJrIjoiODMwMzVlYWMtZmI5Ny00MTlkLTljM2UtMTFmOGZjYjcwYzM0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=041b10097e3900ab64a6
- **Presentation:** https://youtu.be/bZAAo07myGA

## Data Sets and Data Model
The data used in the project consists of the following tables:

- **Dim_customer:** Customer demographic data
- **Dim_date:** Date-related data
- **Dim_policies:** Policy-related data
- **Fact_premiums:** Premium-related data
- **Fact_settlements:** Settlement-related data

A **Star Schema** model was used for the analysis, consisting of 3 dimension tables and 2 fact tables.

## Dashboard Overview

### 1. Home Page
When a user logs in for the first time, they will land on this page, where they can navigate to different pages of the dashboard.

![Screenshot 2025-02-07 152028](https://github.com/user-attachments/assets/ba7c310e-2755-4d01-9287-74ebc8737724)


### 2. General Analysis
Provides an overview of essential insurance metrics, including monthly revenue and customer trends. The segmentation includes age groups and city.

![Screenshot 2025-02-07 155803](https://github.com/user-attachments/assets/500caf00-10e5-4b1b-8033-bbefa860aeec)

### 3. Sales Mode Analysis
Showcases sales performance metrics across different sales channels, including a revenue trend chart highlighting which channel generates the highest revenue.

![Screenshot 2025-02-07 155818](https://github.com/user-attachments/assets/36510dff-bbc6-4f2a-95d1-6b69bf4250e6)

### 4. Age Group Analysis
Demonstrates company revenue and customer performance by age group, including metrics for estimated settlement amounts and policy preferences.
![Screenshot 2025-02-07 155853](https://github.com/user-attachments/assets/06e0159b-89e0-4904-8b78-47d6524fbc88)


## Insights & Recommendations

### Age Group Analysis:
- **Maximum Revenue:** The 31-40 age group generates the highest revenue.

**Recommendations:**
- Focus marketing efforts on the 31-40 age group.
- Tailor policies to attract the 41-50 and 65+ age groups, considering their specific preferences.

### Sales Mode Analysis:
- **Maximum Revenue:** Offline agents generate the most revenue, but online sales have been growing since February 2023.

**Recommendations:**
- Improve customer support and features on the online app and website.
- Implement a system for personalized policy suggestions based on customer details to boost online platform popularity.

### City Analysis:
- **Revenue and Customer Base:** Delhi NCR leads in revenue and customer base, followed by Mumbai and Hyderabad.

**Recommendations:**
- Apply successful strategies from Delhi NCR, Mumbai, and Hyderabad to other cities to increase overall revenue.

### Policy Analysis:
- **Top Policy:** The POL2005HEL policy generates the highest revenue.

**Recommendations:**
- Develop variations of the POL2005HEL policy to attract a wider customer base.
- Offer different rider options to enhance the appeal of the policy.

## Technologies Used
- **Power BI** for dashboard visualization
- **SQL** for data querying and transformation
- **Python** for data analysis and processing
- **Excel** for initial data exploration

## Contact
For any inquiries or collaborations, feel free to connect with me on LinkedIn or GitHub!

---

**Author:** Priya Agrawal
**LinkedIn:** https://www.linkedin.com/in/priya-agrawall/

Access the Power BI Dashboard using the provided link.

Navigate through different pages to analyze various metrics.

Use filters to drill down into specific insights.

Implement the recommendations to improve insurance sales and customer engagement.
