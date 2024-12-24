# Bank Loan Analysis
### Project Overview
This analysis aims to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for user seeking detailed insights into our loan portfolio, borrowers profile and loan performance.
![summary dashboard for bank loan report](https://github.com/user-attachments/assets/d332c7f5-223c-4085-9a41-bb00c87622a7)

![overview dashboard for bank loan report](https://github.com/user-attachments/assets/3c84d045-ee9b-4c86-ad04-0beae3adb54a)

![Details dashboard for bank loan report](https://github.com/user-attachments/assets/098ffe60-b5e7-4943-b8b4-3e8d0e115829)

### Key Performance Indicators, KPIs
The following Key Performance Indicators (KPIs) were used for the dashboards with charts and maps to show trend;
- Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).
- Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.
- Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.
- Average Interest Rate: Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.
- Average Debt-to-Income Ratio (DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans, MTD, and track Month-over-Month (MoM) fluctuations.
### Data Source
Bank Loan Data: The primary dataset used for this analysis is the “bank_loan_data.csv” file containing detailed information about each customer applying for a loan in the bank.
### Tools
- MS Excel- Data Cleaning
- PostgreSQL server- Data Analysis
- Power BI- Creating visuals and reports
### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following:
1.	Data loading and inspection
2.	Handling missing values
3.	Data cleaning and formatting
### Exploratory Data Analysis
- Changing time zone for issue date column on power query
- Creating dynamic measures for one chart to filter multiple column against date column
- Creating group with categorical data column i.e Good/Bad Loan
- Investigating total loan applications, total funded amount, total amount received, average interest rate, average dti
- Creating charts to display trends based on the quality of loan (Good or Bad Loan)

### Data Analysis
This include some intresting code worked with
```sql
SELECT * FROM table
WHERE condition=2:
```
### Result/Findings
The analysis result are summarized as follows:
1. Loan collection increased through the year from January to December
2. Total Amount collected from customers increased through the period

### Limitations
I had to change the time zone for the issue date column to be able to parse the date into PostgreSQL database.
