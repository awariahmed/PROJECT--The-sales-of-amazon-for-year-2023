#AMAZON 2023 SALES AND PERFORMANCE PROJECT
##Comprehensive Project Documentation, Executive Summary &amp; Power BI Implementation

##Guide

##1. Executive Summary
The Amazon 2023 Sales Performance Project provides an exhaustive, data-driven evaluation of e-
commerce transactions executed throughout the fiscal year 2023. Analyzing 6,000 granular order
records representing $378,715.79 in total sales revenue, this project establishes an executive
intelligence framework that examines product category performance, regional distribution patterns,
fulfillment channels, and customer payment behaviors. Designed for executive presentation, this
documentation accompanies the Power BI visualization dashboard to support strategic inventory
planning, regional logistics optimization, and revenue growth initiatives.

##2. Dataset Architecture and Variable Specifications
The underlying dataset (`amazon_sales_2023_project.xlsx`) comprises 6,000 transaction records
structured across thirteen core attributes:
i Order Metadata: Unique Order IDs (`Order_ID`) and precise transaction timestamps (`Order_Date`)
spanning January 1, 2023, through December 31, 2023.
ii Product Taxonomy: Categorization across six major departments (`Product_Category`: Electronics,
Home &amp; Kitchen, Clothing, Beauty, Sports, Books) and specific item descriptions (`Product_Name`).
iiiFinancial Metrics: Unit pricing in USD (`Unit_Price_USD`), order quantities (`Quantity`), applied
discount rates (`Discount_Rate`), and net calculated sales revenue (`Sales_Revenue_USD`).
iv Operational Fulfillment: Shipping methods (`Shipping_Method`: Standard, Expedited, Two-Day) and
customer payment channels (`Payment_Method`: Credit Card, Debit Card, Gift Card).
vGeographical &amp; Status Tracking: Customer states (`Customer_State`), broad sales regions
(`Sales_Region`: South, West, Midwest, Northeast), and order completion statuses (`Order_Status`).

## Key Analytical Findings &amp; Business Insights
Exploratory data analysis of the 2023 sales transactions reveals crucial operational and consumer
behavior patterns:
A. Revenue Contribution by Product Category
Electronics and Home &amp; Kitchen emerge as the dominant revenue generators, capturing the substantial
majority of the $378.7K annual turnover. High unit pricing combined with steady consumer demand in
electronics drives primary top-line growth, whereas books and sports record higher transaction
frequency with lower aggregate revenue contribution.
B. Regional Sales Distribution
Geographic analysis indicates that the South region leads regional performance with 37.0% of total sales
revenue. The West (23.9%) and Midwest (21.6%) demonstrate robust secondary market activity, while
the Northeast accounts for 17.5%, highlighting key geographic clusters for targeted marketing.
C. Fulfillment &amp; Shipping Preferences
Standard shipping accounts for the overwhelming majority of order volume and fulfillment revenue,
reflecting consumer preference for cost-effective delivery options over expedited or two-day tiers.
##4. Power BI Dashboard Implementation Blueprint
To replicate the executive dashboard in Power BI Desktop for supervisory submission, follow this
technical specification:
Core DAX Measures
I Total Revenue: [Total Revenue = SUM(&#39;Sales_Data&#39;[Sales_Revenue_USD])]
II Total Orders: [Total Orders = DISTINCTCOUNT(&#39;Sales_Data&#39;[Order_ID])]
III Total Units Sold: [Total Units = SUM(&#39;Sales_Data&#39;[Quantity])]
IV Average Order Value (AOV): [Average Order Value = DIVIDE([Total Revenue], [Total
Orders], 0)]
Visual Layout Architecture
V Executive Header &amp; KPIs: Top banner styled in Navy Blue (#1F4E78) featuring 4 prominent KPI cards
for Total Revenue ($378K), Total Orders (6,000), Total Units Sold, and Average Order Value.
VII Revenue by Product Category (Bar Chart): A horizontal clustered bar chart ranking product
categories from highest to lowest revenue contribution.
VIII Regional Sales Share (Donut Chart): A percentage-based donut chart displaying revenue distribution
across South, West, Midwest, and Northeast sales regions.
IX Monthly Revenue Trend (Line Chart): A chronological line chart tracking monthly sales performance
throughout 2023 to identify seasonal demand peaks.
X Shipping Method Breakdown (Bar Chart): A comparative column chart illustrating fulfillment
volume and revenue across Standard, Expedited, and Two-Day shipping tiers.

##5. Conclusion and Strategic Recommendations
The Amazon 2023 Sales Performance Project demonstrates the power of structured e-commerce
analytics in uncovering revenue drivers and operational efficiencies. Based on findings from the 6,000-
record dataset, the following recommendations are submitted for executive endorsement:
I Inventory Optimization in High-Value Categories: Prioritize stock availability and supplier
partnerships for Electronics and Home &amp; Kitchen ahead of seasonal peak months to prevent
stockouts.
II Regional Marketing Allocation: Increase promotional expenditure and logistics infrastructure in the
South and West regions to capitalize on existing market dominance.
III Fulfillment Cost Efficiency: Evaluate standard shipping carrier contracts to optimize margins given
its overwhelming volume share among customer fulfillment choices.



South and West regions to capitalize on existing market dominance.
 Fulfillment Cost Efficiency: Evaluate standard shipping carrier contracts to optimize margins given
its overwhelming volume share among customer fulfillment choices.
