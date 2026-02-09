Financial Expense Monitoring Dashboard

Project Overview

This project presents a Financial Expense Monitoring Dashboard developed
using Microsoft Power BI. The objective is to analyze departmental
expenses, identify spending patterns, compare actual costs against
budgets, and support financial decision-making. A custom dataset was
created and used to build interactive visualizations that provide
insights into organizational financial performance.

Dataset Description

Two datasets were used in this project:
1. Clean Dataset 
   Contains structured financial records with the following fields:
     - Date
     - Department
     - Expense Category
     - Amount
     - Budget
     - Vendor

2. Inconsistent Dataset
    Includes missing and irregular values to simulate real-world data issues such as:
     - Missing department entries
     - Blank expense categories
     - Missing amount or budget values
     - Negative or incorrect budget entries
     - Missing vendor information

This dataset was used to demonstrate data validation and cleaning techniques.

Tools and Technologies

-   Microsoft Power BI Desktop
-   DAX (Data Analysis Expressions)
-   Microsoft Excel / CSV Data Sources

Key DAX Measures

-   Total Expenses — Calculates the sum of all expense amounts
-   Total Budget — Calculates total allocated budget
-   Variance — Difference between actual expenses and budget
-   Monthly Average Expense — Calculates average monthly spending
  
  These measures enabled calculation of performance indicators for
dashboard analysis.

Dashboard Features

-   Department-wise expense distribution (Bar Chart)
-   Expense category distribution (Pie Chart)
-   Monthly expense trend analysis (Line Chart)
-   Budget vs Actual comparison (Column Chart)
-   Overspending identification table
-   KPI summary cards
-   Interactive slicers for filtering by department and month

Insights and Findings

-   Operational expenses contributed significantly to total spending.
-   Expense patterns varied across months, showing fluctuations in
    resource utilization.
-   Budget comparison helped identify overspending risks.
-   Data validation highlighted potential issues caused by incomplete or
    inconsistent data.

Recommendations

-   Implement periodic budget monitoring
-   Optimize high-cost categories
-   Conduct regular data quality checks
-   Use forecasting for financial planning

Conclusion

The dashboard demonstrates how business intelligence tools can transform
raw financial data into meaningful insights. By integrating visual
analytics and calculated measures, the solution improves transparency,
supports strategic planning, and enhances cost-control decisions.

------------------------------------------------------------------------
