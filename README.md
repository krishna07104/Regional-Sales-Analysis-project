#📌 Project Title:
USA Regional Sales Analysis – Exploratory Data Analysis

📝 Sub-Headings and Summary of Work Performed
1. Project Introduction
Objective: Analyze Acme Co.'s sales data (2014–2018) to identify revenue/profit drivers across products, channels, and regions.

Goals: Detect seasonal trends, outliers, and compare actuals against 2017 budgets.

2. Importing Libraries
Used pandas, numpy, matplotlib, and seaborn for data handling and visualization.

Configured notebook aesthetics using seaborn styles and custom figure sizes.

3. Data Loading
Loaded an Excel workbook containing multiple sheets:

Sales Orders

Customers

Products

Regions

State Regions

2017 Budgets

Mapped each sheet to separate DataFrames for modular analysis.

4. Initial Data Overview
Checked dataset shapes and schemas using .shape, .head(), and .info().

Identified and handled:

Missing values (especially in budgets)

Data type inconsistencies (e.g., date formats)

5. Univariate Analysis
Analyzed individual variable distributions:

Revenue

Unit Price

Profit Margin

Created bar plots and histograms to visualize sales by product category, region, and channel.

6. Bivariate Analysis
Investigated relationships between:

Revenue and Margin

Quantity Sold and Unit Price

Sales vs. Region and Customer Segment

Used scatter plots and box plots for pattern detection.

7. Trend and Seasonality
Created time-series plots to:

Track monthly and yearly revenue trends.

Identify seasonal spikes and dips in sales (e.g., holiday seasons).

8. Outlier Detection
Detected unusually high/low revenue and unit-price transactions.

Plotted distributions with highlighted outliers.

9. Budget Performance Comparison
Compared 2017 actual sales against forecasted budgets.

Highlighted underperforming and overachieving regions and product categories.

10. Customer Segmentation
Segmented customers using:

Total Revenue

Profit Margin

Visualized customer clusters to identify high-value clients.

11. Correlation Matrix
Generated heatmap to show relationships between numerical variables.

Found moderate to high correlations between revenue and other performance indicators.

✅ Key Tools and Skills Used
Python Libraries: pandas, seaborn, matplotlib, numpy

Techniques: Data cleaning, time-series analysis, outlier detection, clustering, trend analysis

Visualization: Heatmaps, box plots, bar charts, line charts, scatter plots
