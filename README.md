# Datacom GRC Project
## Investigating a cyberattack and producing a comprehensive report"

## INTRODUCTION
This project focuses on investigating a cyberattack by APT34 and producing a comprehensive report, documenting findings and outlining key recommendations for improving a client's cybersecurity posture

## PROBLEM STATEMENT
- One of a leading tech corporation clients has fallen prey to a sophisticated cyberattack by a notorious Advanced Persistent Threat (APT) group known as APT34. The attack, believed to be sponsored by a foreign government, has left the organisation's network compromised and valuable customer data and intellectual property has been stolen.
•	Your mission is to conduct initial research on this APT group, APT34, and assess the extent of the breach's impact on the organisation's information security. But fear not, for you will be provided with all the necessary tools required to understand cybersecurity concepts and principles, including cyberthreats, attack methods, and the importance of confidentiality, integrity and availability of information. In addition, you will also be familiarised with APT34's tactics, techniques and procedures (TTPs) and the common vulnerabilities they exploit to gain access to networks


## AIM OF THE PROJECT
- **Conduct initial research on this APT group, APT34 and assess the extent of the breach's impact on the organisation's information securit
- **Identify APT34's tactics, techniques, procedures (TTPs) and the common vulnerabilities they exploit to gain access to networks

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

## VIZUALISATION
- **Line Chart**
- **Bar Chart**

## RECOMMENDATION
- **Target Top Wastage Causes:** Focus on minimizing the top 10 wastage drivers, especially Time Expiry (TIMEX), which contributes the most to wastage.

- **Optimize RBC Management:** Monitor and manage Red Blood Cell (RBC) stocks carefully due to their consistently high issues and wastage volumes.

- **Adjust for Seasonal Trends:** Align inventory strategies with seasonal and quarterly trends to prevent overstocking during low-demand periods and shortages during peak wastage times (e.g., Q2–Q3 2023).

- **Blood Group-Specific Allocation:** Tailor inventory levels for key blood groups like O Negative and A Negative to address fluctuations in issues and wastage effectively.

- **Enhanced Monitoring of Platelets and Frozen Components:** Closely track and address rising wastage trends in Platelets and Adult FFP, particularly the surges observed in Q1–Q3 2023.

## THANK YOU
