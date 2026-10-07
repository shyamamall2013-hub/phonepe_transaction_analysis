## phonepe_transactions_analysis
this project analyses transaction data to understand transaction volume, transaction value, payment trends, customer behavior and transaction success/failure patterns.

📌 Overview

This project focuses on analyzing PhonePe transaction data using Microsoft Power BI to uncover transaction trends, business performance, and key insights.

The project follows an end-to-end data analytics workflow, including data loading, data cleaning with Power Query, data modeling, KPI development using DAX, Month-over-Month (MoM) analysis, and interactive dashboard development.

The final dashboard enables users to explore transaction performance through interactive visuals, filters, drill-through pages, and report page tooltips.

📂 Dataset

The dataset contains PhonePe transaction data used to analyze digital payment performance across different dimensions such as:

- Transaction volume
- Transaction value
- Transaction type
- Time period
- Payment-related metrics

[📥 Download Dataset]([./Dataset/Phonepe-Final-Dataset.xlsx](https://github.com/shyamamall2013-hub/phonepe_transaction_analysis/blob/main/Phonepe-Final-Dataset.xlsx))

The raw dataset was imported into Power BI and transformed using Power Query before being used for analysis and visualization.

🛠️ Tools & Technologies

📊 Microsoft Power BI
🔄 Power Query
📐 DAX
🗂️ Data Modeling
📈 Data Visualization
📱 PhonePe Transaction Dataset

🔄 Project Steps

1. Data Loading

- Imported the PhonePe transaction dataset into Power BI.
- Reviewed tables, columns, and data types.
- Examined the dataset for data-quality issues.

2. Data Cleaning & Transformation
Used Power Query to prepare the dataset for analysis:

- Removed duplicate records.
- Handled missing and blank values.
- Corrected data types.
- Renamed and standardized columns.
- Cleaned inconsistent values.
- Created required table for analysis.
- Prepared the data for modeling and visualization.

3. Data Modeling
Created a structured Power BI data model to support accurate analysis.

- Established relationships between tables.
- Defined appropriate relationship cardinality.

4. KPI Development Using DAX
Created DAX measures to calculate important transaction KPIs, including:

- Total Transaction Count
- Total Transaction Value
- Success Rate
- Month-over-Month (MoM) Growth
- Transaction performance by category and period

The DAX measures allow KPIs to update dynamically based on user selections and dashboard filters.

5. Month-over-Month (MoM) Analysis
Performed Month-over-Month analysis to understand changes in PhonePe transaction performance over time.

- The analysis helps identify:
- Monthly transaction trends

6. Interactive Dashboard Development
Developed an interactive Power BI dashboard containing:

- KPI cards
- Transaction value analysis
- Transaction count analysis
- Transaction-type comparisons
- Monthly performance analysis
- Slicers and filters
- Drill-through pages
- Report page tooltips

Drill-through functionality allows users to navigate from summary-level insights to detailed transaction analysis, while tooltips provide additional context when hovering over visual elements.

📊 Dashboard
The final dashboard provides an interactive view of PhonePe transaction performance.
Users can:

- Monitor key transaction KPIs.
- Analyze transaction trends over time.
- Compare transaction count and transaction value.
- Perform MoM analysis.
- Filter results using slicers.
- Drill through to detailed analysis.
- View additional information using custom tooltips.
- Dashboard Preview

  [📥 Download Power BI Dashboard](https://github.com/shyamamall2013-hub/phonepe_transaction_analysis/blob/main/phonepe_transactions_analysis.pbix)

Add your Power BI dashboard screenshot here:

![PhonePe Power BI Dashboard](https://github.com/shyamamall2013-hub/phonepe_transaction_analysis/blob/main/Overview.png)

📈 Important Business Insights

-	Transaction Trend: Transaction volume shows an increasing/decreasing trend over the analysed period, with certain months recording significantly higher activity.
-	High Value Customer: Find top 5 high value customers. Focus on these customers to maintain relationship in future.
-	Customer Segmentation: Analysed which age group of customers are performing the high no of transactions.
-	Transaction Type: Certain transaction types account for a larger share of total transaction activity, indicating stronger customer adoption of those services.

🎯 . Business Recommendations

-	Promote underutilized transaction services through targeted campaigns. 
-	Monitor transaction trends to prepare infrastructure for peak periods. 
-	Improve customer support for failed or unsuccessful transactions. 
-	Analyse high-value transaction segments to understand customer behavior.

📁 Project Structure

PhonePe-PowerBI-Analysis/
│
├── data/
│   └── Phonepe-Final-Dataset.xlsx
│
├── dashboard/
│   └── PhonePe_Dashboard.pbix
│
├── images/
│   └── phonepe_dashboard.png
│
├── documentation/
│   └── project_report.pdf
│
└── README.md

👤 Author

Shyama Mall


