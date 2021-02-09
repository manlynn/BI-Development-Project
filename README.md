# 1.Introduction
This solution is for the Business Intelligence Development Project course which was aim to gain the experiences in Agile Business Intelligence development. This solution is for Cronus International Ltd, proving Sales Department, Purchase Department and Logistics Department with the solution for their business analysis according to the user stories. It collected and analyzed users requirements, determined the relevant tables, created the primary key and measures, created start schema, and created the visuals and dashboards.

# 2. Data pre-processing

## 2.1 Deciding the tables and primary keys

- As I would need to use the historical sales data for building the RFM model, I studied how Microsoft Nav store the data. 
- There are dozens of tables in Microsoft which are quite confusing. But it was not so difficult to understand how it sotre the data.
- I found that the active data and closed/archived data are stored in different tables, so I appended the tables.
- But when I tried to connect the data, it created a many to many relationships.
- I did research and found that NAV archives data more than once, therefore, it contains duplicated data.
- So I removed the duplicated data and created the one to many relationship.(pls refer to the final report for the details)

## 2.2 Creating measures

7 measures were created for building the RFM model ( pls refer to the final report for the details)

# 3. Visualization

RFM Analysis

![alt text](https://github.com/manlynn/BI-Development-Project/blob/main/images/RMF.png)


Purchaser workload analysis
![alt text](https://github.com/manlynn/BI-Development-Project/blob/main/images/purchase.png)

