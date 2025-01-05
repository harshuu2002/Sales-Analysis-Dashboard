# Sales-Analysis-Dashboard

1. Introduction
Purpose: "This dashboard was created to analyze and monitor sales performance across multiple dimensions, helping decision-makers gain actionable insights about revenue, customer behavior, and payment trends."

Tools Used: Power BI
<br>
<br>
2. Walk-through of the Dashboard
<br>
<br>
a. Header Metrics
"At the top, we have key performance indicators (KPIs) summarizing the overall sales performance:
<br>
o Total orders
<br>
o Total revenue
<br>
o Unique customers
<br>
o Average value"
<br>
<br>
b. Top Sources and Their Contribution - Bar Chart
This bar chart shows the contribution of different sales channels.
<br>
<br>
c. Payment Status - Pie Chart
The pie chart highlights the payment lifecycle.
<br>
<br>
d. Total Sales by Transactions 
This section shows sales broken down by transaction bank.
<br>
<br>
e. Sales by Currency - Bar Chart
Here, we see sales by currency
<br>
<br>
f. Daily Sales Distribution
The line chart visualizes daily sales trends over time.
<br>
<br>
g. Sales by Language - Bar Chart
This section shows product sales categorized by language or type.
<br>
<br>
h. Top 5 Users by Spends
This bar chart lists the top spenders, like User5965 (0.15M), helping target high-value customers
<br>
<br>
i. Revenue by Payment Mode and Source
This stacked chart shows how different sources contribute to revenue by payment mode.
<br>
<br>
j. Filters
<br>
<br>
"Filters allow users to drill down into specific months or languages, making the dashboard dynamic and customizable for detailed analysis."

Challengers - 
1.Columns like Transaction Bank, Payment Mode, and Coupon Code have missing or blank values.
2.No single column uniquely identifies transactions.


Overcome - 
1.Generate composite keys (e.g., User ID + Product Code + Sales Date).
2.Always validate the uniqueness of generated keys.


Learnings - 
1. Focus on clarity and avoid overloading visuals with too many variables.
2. Prioritize visuals that directly answer key business questions.
