# Personal Finance Analysis

## Table of Contents
- [Objective](#objective)
- [Key Requirements](#key-requirements)
- [Tools Used](#tools-used)
- [Data Source](#data-source)
- [Data Loading](#data-loading)
- [Data Cleaning](#data-cleaning)
- [Reporting Wireframing](#reporting-wireframing)
- [Dashboard](#dashboard)
- [Inferences](#inferences)
- [Conclusion](#conclusion)

## Objective
This Github documentation aims to demonstrate the end-to-end process of Personal Finance Data Analysis project, which is a comprehensive analysis of my financial statements, shedding light on my income, expenditure, and investments.

## Key Requirements
**i. KPIs:**
   - Available Balance
   - Total Income
   - Total Expenditure
   - Total Savings
   - Total Investments

**ii. Income Analysis:**
   - Income Trend over Time
   - Breakdown of Income by Different Sources

**iii. Expenditure Analysis:**
   - Expenditure Trend over Time
   - Breakdown of Expenses by Categories showcased as both Percentage as well as Actual Amount

**iv. Investments:**
   - Allocation of Funds by different Assets
   - Change in Savings & Investments over Time

## Tools Used
- Data Loading and Cleaning - Microsoft Excel
- Reporting Wireframing - Microsoft Power Point
- Data visualization - Tableau

## Data Source
Consolidated bank statements retrieved from the net banking portal formed the primary data source, capturing most financial transactions. It should be noted that while the data is primarily sourced from banking transactions, not all expenses are accounted for, particularly those involving small-value payments made through digital platforms like Paytm or in cash.

Since the information presented in this project pertains to my personal and confidential information, not all figures are actual, for instance: income and some expenses. This version of the analysis, available as a public repository is to showcase my competency in working with data.

## Data Loading
The data preparation stage involved loading the source data into Excel and identifying the limitations of data that may cause obstacles in the analysis and reporting. 
In this case, the personal financial statements, stored as PDF documents, were downloaded to the local storage from the bank's portal and loaded into Microsoft Excel.

![image](https://github.com/tusharkalal20/Personal-Finance-Project/assets/67863411/12b1fd6b-c157-47ee-85bb-9a516ee595a7)

**Challenge:** Due to the confidential nature of financial statements, they are commonly encrypted with a password to prevent unauthorized access. This encryption, however, posed a challenge in establishing an Excel connection to the PDF files and loading the data into a spreadsheet. To address this issue, I utilized a PDF tool to decrypt the file, enabling the extraction and transfer of data into the spreadsheet.

## Data Cleaning
Once the data is loaded, a pop-up occues containing a preview of different tables present in the connected pdf file. Please note that not all tables are required for our analysis as some contain personal information stored with the bank, we can simply ignore them and choose to not load it into our spreadsheet.

Below is a preview of the same:

![image](https://github.com/tusharkalal20/Personal-Finance-Project/assets/67863411/7bef3b28-7e3e-467c-8c02-4db361e40386)


As is evident, the raw data has some quality issues which need to be addressed.
- **Unnamed Columns:** Labeling the fields is important to seamlessly conduct analysis and create reports 
- **Null Values:** There are cells with null values which need to be mindfully discarded
- **Date formatting:** I have formatted the date to 'dd-mm-yy' format and created an additional column that stores the date information in mm/dd/yy (US format)
- **Data Labelling:** A crucial requirement to conduct the required analysis is to have the description of each transaction and the categorization by 'Type' and 'Component'.

## Reporting Wireframing
In an effort to establish the foundational structure of the dashboard and generate the necessary reports, I used Microsoft Powerpoint for the initial design. Please note that this serves as a reference, and adjustments to the chart layout may be necessary once actual data is incorporated. Regardless, it provides a solid starting point for visualizing the potential outcome.

![image](https://github.com/tusharkalal20/Personal-Finance-Analysis/assets/67863411/0136d925-7e47-4045-b2e6-19c466be02fe)

Below is a break-down of the interface:

![Dashboard Canvas Breakdown](https://github.com/tusharkalal20/Personal-Finance-Analysis/assets/67863411/6c436588-7c9d-492a-952e-26d9ee4a0d73)


## Dashboard
You can visit the Tableau dashboard here [Personal Finance Dashboard](https://public.tableau.com/app/profile/tushar.kalal/viz/PersonalFinanceDashboard2/Dashboard)

![Dashboard Image](https://github.com/tusharkalal20/Personal-Finance-Project/assets/67863411/0a789ea5-4049-4a2e-a19f-61906e32e84a)



## Inferences
**i. Observations on Income:**
- Analyzing the line graph, it is evident that income exhibited growth starting in 2020, with a substantial increase in 2022.
- I started working in 2021; thus, until that year, income predominantly consisted of savings interest on the existing amount.
- The apparent decline in 2023 is attributed to the data capture being limited to June 2023, accounting only half of the income for that year.
- The breakdown of income sources reveals that **full-time salary constituted ~77% of the total income**, followed by internship stipends at 18%, income earned through teaching mathematics at 4%, and savings interest income at 0.8%.


**ii. Observations on Expenditure:**
- Expenses experienced a moderate decline from 2019 to 2020, but they showed a continuous upward trend from 2020 onward, indicating **a positive correlation between the increase in income and the rise in expenses.**
- My primary areas of expenditure, constituting the majority of my spending, are as follows:
   - Insurance & Medical - 33% (A significant portion of this amount was allocated to an ear procedure, followed by family health insurance covering a two-year period).
   - Wedding – 16%
   - Utilities – 14% (includes groceries, society maintenance, internet, gas, telephone, and fuel)
   - Food – 9% (includes expenses from both dining out and fast-food consumption)
   - The average monthly expenses amount to INR 16,000.

**iii. Savings & Investments:**
   - Over the course of five years, a total of 70,000 INR was set aside for savings and investments, implying that **only 8% of the money was saved/invested**. This figure is notably low and requires a substantial increase. Contributing factors to the modest savings and investments could be attributed to two main reasons:
      - Failure to allocate sufficient funds to investments.
      - Insufficient available funds for saving and investing.
   - Our analysis suggests that the **lack of investments stems from insufficient available funds for saving and investing due to high expenses (71% of the total income).** To identify potential areas for savings, a comparison between essential and discretionary spending was carried out 
      - It was found that **49% of the expenses are deemed necessary and unavoidable**.
      - However, a significant portion of the remaining expenses, such as those related to the wedding and frequent dining out, movies, entertainment could have either been reduced or entirely avoided.
