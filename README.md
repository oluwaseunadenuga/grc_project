# grc_projects
# IHS HOSPITAL COMPONENT ISSUES & WASTAGE ANALYSIS 
## Leveraging MS Excel and Power BI to Optimize Blood Component Management by Uncovering Insights into Issues, Wastage, and Inventory Management
![image](https://github.com/user-attachments/assets/c4f0e9b5-7ab5-4902-ba68-374c94a38615)

***Disclaimer⚠️:** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis on healthcare dataset*
## INTRODUCTION
The **IHS Blood Stocks Management** aims to enhance blood inventory management across the supply chain. This project utilizes Power BI to analyze hospital component issues and wastage trends, focusing on Red Blood Cells, Platelets, and Frozen Plasma. Key insights reveal strong issue-wastage correlations, seasonal patterns, and major wastage causes like Time Expiry (TIMEX). The findings offer data-driven recommendations to optimize inventory management and minimize wastage for NHSBSM.
![image](https://github.com/user-attachments/assets/b256cb67-793a-4229-94ab-b1581ecf4cad)

## PROBLEM STATEMENT
- Hospitals face challenges in managing blood component inventory, leading to high wastage and supply inefficiencies.
## AIM OF THE PROJECT
- **Analyze Trends:** Identify patterns in hospital component issues and wastage using Power BI to understand their correlation and root causes.
- **Optimize Inventory Management:** Provide data-driven insights to reduce wastage, especially from Time Expiry (TIMEX), and improve blood supply efficiency.
- **Enhance Decision-Making:** Support IHSBSM with strategic recommendations for better forecasting, allocation, and utilization of blood components.

## METHODOLOGY 
- **Business Understanding:** I defined project objectives to analyze trends in NHS hospital
component issues and wastage.
- **Data Understanding:** I explored the dataset to identify key features and
relationships for analysis.

- **ETL Process:** I extracted, transformed, and loaded the data into Power BI for
compatibility and analysis.

- **Data Modeling:** I created relationships between fact and dimension tables for
structured analysis.

- **Analysis & Visualization:** I used Power BI to generate trendline charts and
visualizations, uncovering correlations and patterns in issues and wastage.

## MODELLING
The data modeling for this project follows a star schema approach, where the **Fact Table** (containing hospital component issues and wastage records) is connected to multiple **Dimension Tables** to ensure efficient analysis. The **Fact Table** includes key metrics such as issue counts, wastage counts, product group names, and blood group names. It is linked to **Dimension Tables** like **Blood Group (O-, A+, etc.), Calender (Year, Quarter, Month), and Wastage Codes (TIMEX, TTMH, etc.)** through unique identifiers. This relational structure allows for seamless trend analysis, comparisons across different categories, and deeper insights into the root causes of wastage and inventory inefficiencies.

![image](https://github.com/user-attachments/assets/2e3e66b0-be62-4eff-affd-e1f42defe90c)

## VIZUALIZATION
- **Line Chart**
- **Bar Chart**

## RECOMMENDATION
- **Target Top Wastage Causes:** Focus on minimizing the top 10 wastage drivers, especially Time Expiry (TIMEX), which contributes the most to wastage.

- **Optimize RBC Management:** Monitor and manage Red Blood Cell (RBC) stocks carefully due to their consistently high issues and wastage volumes.

- **Adjust for Seasonal Trends:** Align inventory strategies with seasonal and quarterly trends to prevent overstocking during low-demand periods and shortages during peak wastage times (e.g., Q2–Q3 2023).

- **Blood Group-Specific Allocation:** Tailor inventory levels for key blood groups like O Negative and A Negative to address fluctuations in issues and wastage effectively.

- **Enhanced Monitoring of Platelets and Frozen Components:** Closely track and address rising wastage trends in Platelets and Adult FFP, particularly the surges observed in Q1–Q3 2023.

## THANK YOU
