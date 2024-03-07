## Customer Segment Analysis using RFM model

## Goal of the project
The objective is to conduct a Customer Segment Analysis for an automobile bike company utilizing the RFM (Recency, Frequency, Monetary) model. This behavior-based approach categorizes customers into segments to determine which segments should be targeted for enhanced sales revenue.

## Analysis Techniques:
### 1.	Data Quality Assessment and Data Cleaning

- Understand the data, checking for relevance, missing values, and duplicates.
-	Utilize multiple datasets (Transactions, New Customer List, Customer Demographic, and Customer Addresses).
  
Implement key processes:
-	Check data information (data types, row/column count).
-	Address missing values.
-	Remove irrelevant features.
-	Eliminate duplicate data entries.
-	Manage data outliers.
-	Ensure data consistency for accurate analysis.

### 2.	Exploratory Data Analysis on Customer Segments

#### a)	New vs Old Customer Age Distribution
-	Analyze new customer lists and old customer datasets.
-	Majority of customers fall within the 40-49 age group.
-	Lowest number of customers below 20 and above 80.
-	Note a drop in the 30-39 age group among new customers.

#### b)	Bike purchased over last 3 years by gender
-	Women constitute approximately 51% of total bike purchases.
-	Female purchases exceed 9500, surpassing male purchases in the count.

#### c)	New vs old customers Job Industry distribution
-	Most new customers are from manufacturing and financial services.
-	The lowest number of customers are from Agriculture and Telecommunication.

#### d)	Wealth Segmentation by Age Category
-	Across all age categories, the largest customers are in the "Mass Customer" segment.
-	Among new customers, affluent customers surpass high-net-worth individuals in specific age groups.

#### e)	Car owns across each state
-	In NSW, most people don't own a car.
-	Victoria shows a relatively even car ownership proportion.
-	In Queensland, more people own a car than those who don't.

## RFM Analysis and Customer Segmentation

In this stage of analysis, the customer segmentation was done by developing an RFM Model. The RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach grouping customers into segments. It groups the customers based on their previous purchase transactions. Here, the customer segment was divided into 11 groups. The groups are:

- Platinum Customers
- Very Loyal Customers
- Recent Customers
- Potential Customers
- Lost Customers
- Losing Customers
- Late Bloomer
- High-Risk Customers
- Evasive Customers
- Becoming Loyal
- Almost lost Customers

### Datasets used

The dataset includes [Raw Data](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/Raw_data.xlsx) file having different sheets inside it. The sheets are: Transactions, New Customer List, Customer Demographic, and Customer Addresses.

### Python Files
- [RFM Analysis](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/RFP_Analysis.ipynb)
- [Data Cleaning - Transactions](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_Transcation.ipynb)
- [Data Cleaning - New Customer List](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_New_Customer_List.ipynb)
- [Data Cleaning - Customer Demographic](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_Customer_Demographic.ipynb)
- [Data Cleaning - Customer Addresses](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_Customer_Address.ipynb)

