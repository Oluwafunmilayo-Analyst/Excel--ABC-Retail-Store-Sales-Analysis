
![TSA final Dashboard](https://github.com/user-attachments/assets/292653ca-8369-4395-8a4e-c3b420c61a0c)


## ABC Retail Store Sales Analysis
---

### Table of Content
  - [Project Overview](#project-overview)
  - [Data Source](#data-source)
  - [Tools]($tools)
  - [Data Cleaning and Preparation](#data-cleaning-and-preparation)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Data Analysis](#data-analysis)
  - [Key Findings and Visualizations](#key-findings-and-visualizations)
  - [Recommendations](#recommendations)
  - [References](#references)

### Project Overview
---
ABC Retail Store is a regional retailer specializing in Electronics, Furniture and Home Appliances. This Data analysis project aims to provide insight into the Sales Performance for the year 2025. The Management could not easily identify which products contribute most to the bottom line versus those that just have high sales volume. Operational costs (COGS) are rising in certain cities without a clear explanation. Monthly sales trends are inconsistent, and the company needs to identify “slump” months to better plan marketing campaigns. 
By analyzing Various aspect of the Sales data, we seek to create an interactive executive dashboard to monitor KPIs, identify the product with the highest profit,evaluate sales representative performance, Cost of Goods Sold by Citiesand Monthly Customer Trend.
 
### Data Source
---
The Dataset used for this project is attached for your reference

### Tools Used: 
---
  - Microsoft Excel(Power Query, Pivot Tables, Pivot Charts) - Data Cleaning, Analysis and Visualization
    
[Download here](https://Microsoft.com)

### Data Cleaning and Preparation
---
In the data preparation phase, the following task was performed:

1. Data loading and inspection : The dataset was verified that Unit Price, Quantity and Cost Price were numerical types and that the Dates field were consistently formatted to allow for Time Series analysis

2. Handling Missing Values : The Data was inspected for missing and Null Values. The data did not need so much cleaning.

3. Data Cleaning: Power Query (Data > Get Data) was used to remove duplicates and ensure dates are formatted correctly. There was no duplicate in this dataset.
  
### Exploratory Data Analysis
---
EDA invloved reploring the sales data to answer key questions such as:
  - What Product had the highest profit?
  - Which Sales Rep gave the highest and lowest Revenue?
  - What City had the highest Cost of Goods Sold?
  - What Month of the year had the highest and Lowest Customer Count?
    
### Data Analysis
---
This include the formulars used during Analysis

``` Excel Formulars

COGS = Cost Price * Quantity

Revenue = Unit Price * Quantity

Profit =Revenue - COGS
```

### Key Findings and Visualizations
---
The Analysis Results are Summarized as follows:

1. **KPIs:**

  - Total Revenue: N2,328,370,000
    
  - Total COGS: N1,862,696,000
    
  - Total Profit: N465,674,000 (Margin:20%)
    
  - Total Customer Transactions: 2,098
    
2. **Product by Profit:** Laptop A13 is the most profitable product N105.3M Profit, while Blender B10 is the least.
   
  ![Product by Reven](https://github.com/user-attachments/assets/8107e033-0aa4-4d39-984a-4b1881765a60)

3. **Sales Rep by Revenue:** Peter is the top performer N434.8M, followed closely by Musa.
   
   ![Sales rep](https://github.com/user-attachments/assets/4691b4de-22c4-475d-9a89-9c53cc9bd3ac)

4. **City by COGS:** Lagos has the highest Cost of Goods Sold N493.8M, indicating it is the most expensive hub to operate.
   
![Location by COGS](https://github.com/user-attachments/assets/8ae9ac3d-cf3c-4a9d-b74c-b53e036e067d)

5. **Monthly Customer Trend:** April was the peak month (536 transactions). May is the worst performing month (18 transactions)
   
![month by customer](https://github.com/user-attachments/assets/ff719416-f185-4f74-a1fd-52a027ec3620)

Note: If May is the current month, this might indicate incomplete data; otherwise, it marks a severe seasonal drop.

### Recommendations
---
1. **Product Strategy:** Double down on Laptop A13 marketing. Since it generates the highest profit, even a small increase in its sales volume will significantly impact the company's total profit compared to Home Appliances.

2. **Regional Optimization:** Conduct a "Cost Audit" in Lagos and Kano. These cities have the highest COGS. Negotiating better warehouse rates or local logistics contracts in these hubs could save millions.

3. **Sales Mentorship:** Pair the top rep, Peter, with Grace (who has the lowest revenue). Implementing a peer-mentorship program can help standardize "closing" techniques across the team.

4. **Seasonal Campaign:** Launch a "May Recovery" promotion. The data shows a massive drop in customers in May. Offering "Early Bird" discounts or loyalty rewards during this period could help stabilize the annual revenue stream.

### References
1.Google

2.Gemini

3.TS Academy
