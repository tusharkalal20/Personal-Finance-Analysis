# Personal-Finance-Project

## Objective
This Github documentation aims to demonstrate the end-to-end process of Personal Finance Data Analysis project, which is a comprehensive analysis of my financial statements, shedding light on patterns in income, expenditure, and investments.

## Key Requirements
1. KPIs:
   - Total Income
   - Total Expenditure
   - Total Savings
   - Total Investments

2. Income Analysis:
   - Breakdown of Income by Different Sources

3. Trends:
   - Income Trend over Time
   - Expenditure Trend over Time
   - Correlation between Income Growth and Expenditure

4. Expense Categories:
   - Categorization of Expenses by Percentage and Amount

5. Investments:
   - Allocation of investments by Assets
   - Present Value of Investments

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

![image](https://github.com/tusharkalal20/Personal-Finance-Project/assets/67863411/a6b9da25-5515-4b95-95cb-d3faa0ad36fd)


Below is a preview of how the data looks in one of the yearly statements:

![Snapshot](https://github.com/tusharkalal20/Personal-Finance-Project/assets/67863411/f2bf68ed-5cf6-466c-8f0a-70d9edfc0837)


As is evident, the raw data has some quality issues which need to be addressed.
- Unnamed Columns
- Null Values
- Date formatting
- Data Labelling: A key requirement to conduct the required analysis is to have the description of each transaction and categorize with 'Type' and 'Component'.
- Data Loading: Since a financial statement contains confidential information, it is typically encrypted with a password to prevent unauthorised use. This encryption inhibited the creation of an Excel connection to the pdf files and load the data into a spreadsheet. To remediate this situation, I decrypted the file using a pdf tool.

## Inferences
**1. Observations on Income:**
- From the line graph, it can be inferred that my income started seeing growth from 2020 and grew by a high amount in 2022. 
- I started earning in 2021. Hence, up until 2021 income comprised primarily of savings interest on the existing amount. 
- The decline in 2023 is only because this data has been captured till June 2023 which only account half of 2023 income.
- Full-time Salary formed around 77% of the Total Income while Stipend contributed 18% followed by Tutoring (4%) and Savings Interest Income (0.8%).


**2. Observations on Expenditure:**
- Expenses dropped moderately from 2019 - 2020 but kept increasing from 2020 implying a positive correlation between Increase and Expenses.
- My top 4 areas where I spent the most on are:
   - Insurance & Medical - 33% (A big chunk of this went into ear procedure followed by family health insurance paid for 2 years)
   - Wedding – 16%
   - Utilities – 14% (includes Groceries, Society Maintenance, Internet, Gas, Telephone, Fuel)
   - Food – 9% (includes both Dining Out and Fast-Food expenses)
- The Average Monthly Expenses is INR 16K


**3. Savings & Investments:**
   - A total of 70K in Savings & Investments makes about a meagre 8% of the Total Income across a period of 5 years. This is a very small figure that needs to be drastically increased. A small contribution to Savings & Investments could primarily be because of 2 reasons:
      - Failure to allocating funds to investments
      - Lack of available money to save and invest

It is evident from our analysis that the reason why investments were not made is because of high expenses(71% of the total money earned) in turn leading to a lack of available money dispensable to invest. To further investigate, there is merit in comparing my expenditure made on necessary things v/s leisure things that could potentially have been avoided. 
