# CRM-Salesforce-Analytics-Project
CRM analytics software refers to tools that allow businesses to analyze data collected through their Customer Relationship Management (CRM) Systems. This analysis helps in understanding customer behavior, optimizing sales, marketing strategies, and improving overall business performance. Salesforce is one such CRM tool on which this project is based.

![Salesforce Logo](https://github.com/user-attachments/assets/75c7bf0a-598c-4bb4-9280-e5d151ea08be)

## Introduction
This project provides a complete end-to-end data analytics workflow for CRM (Salesforce). The goal is to extract valuable business insights using Excel, SQL, Tableau, and Power BI.

## Project Objectives
- Export, transform, and load the data (ETL).
- Create a data model.
- Find the key performance indicators/metrics (KPIs).
- Perform the exploratory data analysis (EDA).
- Visualization.

## Project KPIs To Find
Opportunities KPIs: 

- Total Expected Amount.
- Active/Open Opportunities.
- Conversion Rate.
- Win Rate.
- Loss Rate.
- Trend Analysis of: Expected Vs Forecast, Active Vs Total Opportunities, Closed Won Vs Total Opportunities, Closed Won Vs Total Closed Opportunities.
- Expected Amount by Opportunity Type.
- Opportunities by Industry.

Lead KPIs: 

- Total Leads.
- Expected Amount from Converted Leads. 
- Lead Conversion Rate.
- Converted Accounts.
- Converted Opportunities.
- Lead By Source.
- Lead By Industry.
- Lead by Stage/Status.

## About The Datasets
Total 5 Datasets:

- Account: 3,052 rows x 58 columns. It contains company data like account type, rating, billing information, industry, and revenue.
- Lead: 10,000 rows x 93 columns. It contains lead data like conversion status, city, lead score, campaign details, and source.
- Opportunity: 4,646 rows x 88 columns. It contains sales opportunity data like account ID, close date, amount, status (won/lost), and probability.
- Opportunity Product: 10,000 rows x 23 columns. It contains product-level data tied to opportunities like sales price, product ID, quantity, and total price.
- User: 98 rows x 143 columns. It contains user data like their roles, active status, and locations.

## Key Fields For Analysis
- Industry, Account Name, Account Type, Created Date, and Rating.
- Lead Source, Status, Created Date, Last Status Change Date, Converted Accounts, Converted Opportunities, Marketing Segmentation, Product Category, Total Leads, and Industry.
- Lead Source, Stage, Closed, Won, Expected Amount, Probability, Close Date, Account ID, Owner ID, Account Type, and Product Category.
- Product Name, Quantity, Total Price, Discount, and Opportunity ID.
- Department, Full Name, Profile ID, Manager ID, and Active.

## Key Stats
- Top industries.
- Top opportunity types. 
- Top product categories.
- Lead source performance.
- Performance rates.
- Time trends.
- Most common stages/statuses (Nurturing, Prospect).
- Conversion funnel.
- Sales pipeline.
- Revenue growth.
- Different opportunities.
- User to opportunity and lead.

## The Process On Different Software
- In Excel: Corrected columns data types, replaced certain null values with the term unknown, replaced certain other values accordingly too, added a few columns more, cleaned the datasets off duplicates/blank rows/errors, and merged a few queries on Power Query.

![Project ETL](https://github.com/user-attachments/assets/7225b782-f0c6-4373-909b-5d10fabbdce9)

- In SQL: Loaded the cleaned datasets from above and written queries to find the project KPIs.

![Project SQL](https://github.com/user-attachments/assets/b52a19ab-b504-4bbd-8940-327ce5a6fc60)
![Project SQL 2](https://github.com/user-attachments/assets/4380e5d3-d230-4ea9-bc17-e67000813a30)
![Project SQL 3](https://github.com/user-attachments/assets/abfabefc-2398-4187-a45b-4063e4252d61)
![Project SQL 4](https://github.com/user-attachments/assets/ce03e4f4-7586-4177-9928-4c8a980ad58d)
![Project SQL 5](https://github.com/user-attachments/assets/339a5b30-a759-49c8-86c8-4bfe21ce140c)
![Project SQL 6](https://github.com/user-attachments/assets/ecfaa2c0-27ec-4b61-9aea-d514c175aa00)
![Project SQL 7](https://github.com/user-attachments/assets/d2dadc73-a642-43af-a63c-79980383e8a4)
![Project SQL 8](https://github.com/user-attachments/assets/b3fef9a0-d00b-4c38-82b8-881ff7807bd9)

- In Tableau: Did the data blending with the cleaned datasets, added certain calculated fields, found the KPIs, performed some EDA, and made a dashboard.

![Project Tableau Dashboard](https://github.com/user-attachments/assets/f6954b2b-0004-4236-9702-de16b5b64fa7)
![Project Tableau Dashboard 2](https://github.com/user-attachments/assets/0515f325-7fa3-4854-a0fd-8c82a3b41310)
![Project Tableau Dashboard 3](https://github.com/user-attachments/assets/8c3b7e1b-0bcc-477d-9f49-99e054ccfa18)
![Project Tableau Dashboard 4](https://github.com/user-attachments/assets/5e47aa5e-9992-486e-853c-f92cb18eaa8d)

- In Power BI: Done the data modeling between the cleaned datasets, added required DAX measures, found the KPIs, performed some EDA, and made a dashboard.

![Project Power BI Dashboard](https://github.com/user-attachments/assets/67c205a4-88a8-484c-a545-444d161560ab)
![Project Power BI Dashboard 2](https://github.com/user-attachments/assets/fb67d4b5-aa37-4149-9024-29e000c36ed2)
![Project Power BI Dashboard 3](https://github.com/user-attachments/assets/16203792-592c-4a64-b536-f9f09ecb5390)
![Project Power BI Dashboard 4](https://github.com/user-attachments/assets/8507b9f8-6598-4786-b9b7-363848fca2a4)

- In Short: I used Excel to perform ETL; SQL to find the specified project KPIs; Tableau and Power BI to find the KPIs, perform some EDA, and visualize the data.

## Overall Project Analysis
Opportunity:

- ✅ Pipeline Status: There are currently a fair no. of opportunities, though more are required.
- 💰 Revenue Growth: The expected deal revenue is mostly aligned with the targets.
- 🏆 Performance Rates: The win rate is decent, though the loss rate needs to go down.
- 📦 Opportunity Types: A few specific opportunity types control the expected revenue.
- 🏭 Industry Focus: A few industries are driving the most deals, indicating more expansion.
- 🌍 Geographic Spread: Key countries are driving the expected revenue.
- 📈 Forecast Vs Expected Revenues: Forecast and expected revenues peaked from 2020 to 2021 but then dropped, indicating potential over forecast or less opportunity creation.
- 🟢 Total Vs Active Opportunities: Total and active deals peaked from 2019 to 2021 but then dropped, indicating pipeline shortcomings.
- 📊 Total Vs Closed Won Opportunities: Total and won deals dropped after 2021 with fewer to no wins, indicating sales execution gaps.
- 🎯 Total Closed Vs Closed Won Opportunities: Total closed and won deals dropped after 2020 with fewer to no wins, indicating sales execution gaps again.
- 🥇 Top Deals: A few large opportunities are the higher priority right now.

Lead:

- 🔢 Lead Volume: There are currently a fair no. of leads, though more are required here as well.
- 🔄 Conversion Rate: Around 10.16% of leads are converting into opportunities or accounts/customers.
- 💰 Revenue Growth: The expected deal revenue from the leads is mostly aligned with the targets here as well.
- 📣 Lead Sources: Most leads are coming from just a few sources.
- 📉 Lead Funnel: This shows how leads are flowing through the process and where we are losing them. There is a significant drop-off from the nurturing to the qualification stage/status.
- 🧭 Lead Industries: Some industries are significantly contributing more leads whereas others are overly underutilized, indicating more expansion here as well.
- 🎯 Lead Creation Vs Conversion: Leads created and converted are increasing every year, though more focus is required in the conversion area.

## Conclusion:
There is a strong base of leads and opportunities, but the gaps in conversion, pipeline forecasting, and data quality are holding back performance. By improving lead management, marketing, expansion, sales execution, and CRM routine, the organization can:

- Increase win and conversion rates.
- Improve forecast accuracy.
- Protect margins.
- Maintain sustainable revenue growth.
