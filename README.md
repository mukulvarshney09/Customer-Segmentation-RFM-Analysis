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

![WhatsApp Image 2024-03-07 at 2 32 32 PM](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/64a3f4d2-1867-4506-ba62-c812aba3e43a)

#### b)	Bike purchased over last 3 years by gender
-	Women constitute approximately 51% of total bike purchases.
-	Female purchases exceed 9500, surpassing male purchases in the count.

![3](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/0d1e82fa-666e-4921-81a2-306bf8a26bbf)

#### c)	New vs old customers Job Industry distribution
-	Most new customers are from manufacturing and financial services.
-	The lowest number of customers are from Agriculture and Telecommunication.

![1](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/4ee13b97-8074-4678-9636-af7fbb454e25)
![2](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/5e159678-27ca-45b3-90aa-b64104b42fa5)

#### d)	Wealth Segmentation by Age Category
-	Across all age categories, the largest customers are in the "Mass Customer" segment.
-	Among new customers, affluent customers surpass high-net-worth individuals in specific age groups.

![3](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/a6298668-c096-478e-b28b-d50ea8d94f0e)
![4](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/6fc8e5c3-b10b-4ed5-9605-ffef7d117b59)

#### e)	Car owns across each state
-	In NSW, most people don't own a car.
-	Victoria shows a relatively even car ownership proportion.
-	In Queensland, more people own a car than those who don't.

![5](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/1509e5fd-0210-44ba-a771-264e4b6d64fc)

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

![6](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/b4cff93c-d744-4ff1-bd96-05f15adbc8bb)

## RFM Analysis: Scatter Plots
### Recency vs Monetary:
The visualization shows that recent customers have purchased more products and generated relatively more revenue than the customers who visited a while ago.

![7](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/1e9048da-52f1-4cc0-a40a-631edc95b164)

### Frequency vs Monetary:
The visualization shows that customers belonging to Platinum/ Very Loyal/ Becoming Loyal Customer Segments have a greater frequency and generate greater monetary for the business.

![8](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/assets/123244732/127a693c-0fca-468a-90be-6ec951308f07)

### Datasets used

The dataset includes [Raw Data](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/Raw_data.xlsx) file having different sheets inside it. The sheets are: Transactions, New Customer List, Customer Demographic, and Customer Addresses.

### Python Files
- [RFM Analysis](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/RFP_Analysis.ipynb)
- [Data Cleaning - Transactions](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_Transcation.ipynb)
- [Data Cleaning - New Customer List](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_New_Customer_List.ipynb)
- [Data Cleaning - Customer Demographic](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_Customer_Demographic.ipynb)
- [Data Cleaning - Customer Addresses](https://github.com/mukulvarshney09/Customer-Segmentation-RFM-Analysis/blob/main/DQA_Customer_Address.ipynb)

