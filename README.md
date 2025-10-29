# Datacom GRC Project
## Investigating a cyberattack and producing a comprehensive report"

## INTRODUCTION
This project focuses on investigating a cyberattack by APT34 and producing a comprehensive report, documenting findings and outlining key recommendations for improving a client's cybersecurity posture

## PROBLEM STATEMENT
A leading tech corporation clients has fallen prey to a sophisticated cyberattack by a notorious Advanced Persistent Threat (APT) group known as APT34. The attack, believed to be sponsored by a foreign government, has left the organisation's network compromised and valuable customer data and intellectual property has been stolen.

## PROJECT OBJECTIVES
- **The objective of this project is to help our client conduct an initial investigation into APT34 and evaluate the potential impact of the attack on the organisation:**.
- **Produce a comprehensive report documenting your findings and outlining key recommendations for improving the organisation's cybersecurity posture:**

## OSINT TOOLS
OSINT tools used to gather information on APT34:
- **Mandiant Security Blog: https://www.mandiant.com/resources/blog:**
- **CrowdStrike: https://www.crowdstrike.com:** 
- **Recorded Future: https://www.recordedfuture.com:** 
- **CyberScoop: https://www.cyberscoop.com:**
- **Dark Reading: https://www.darkreading.com:**
- **The CyberWire: https://thecyberwire.com:**
- **SecureWorks - https://www.secureworks.com:** 
- **ThreatConnect - https://www.threatconnect.com:** 
- **Kaspersky Lab: https://www.kaspersky.com:**
- **Symantec Threat Intelligence: https://www.symantec.com/threat-intelligence:**

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
