# Supplier Performance & Profitablity Analysis-Dashboard-SQL-Power-BI-Python (Pandas, NumPY)
 **SQL, Python, Excel and Power BI**

**Overview**

This project analyzes supplier sales, pricing, and inventory data to understand what drives profitability and where operational issues may exist. The goal was to identify opportunities to improve purchasing decisions, pricing strategy, and inventory management in a retail or wholesale setting.

**Business Objective-**

Companies can lose profit due to inefficient pricing, slow-moving inventory, or overdependence on a few suppliers. This analysis was conducted to:

- **Identify products that may need pricing or promotional changes**

- **Determine which suppliers contribute most to purchases and revenue**

- **Evaluate the cost benefits of bulk purchasing**

- **Assess inventory turnover and unsold stock**

- **Compare profitability across different supplier groups**

These objectives reflect the key business questions outlined in the project report. 

**Supplier Performance Report**

**Data Description**

The dataset contains transaction-level information related to suppliers, products, purchases, sales, pricing, and costs. Key fields include:

- Purchase and selling prices

- Sales quantities and revenue

- Profit and profit margins

- Freight costs

- Inventory levels

- Supplier and product identifiers

- Data cleaning steps included removing records with zero sales and loss-making transactions to focus on meaningful performance patterns. 


**Analysis Performed**
**- Exploratory Data Analysis**

Initial analysis revealed pricing outliers, negative profit cases, and large variation in freight costs, suggesting inconsistencies in procurement and logistics. Some products showed zero sales despite being purchased, indicating potential obsolete or slow-moving stock. 



**Supplier Contribution-**

A small group of suppliers accounts for a large share of purchases. The top ten suppliers contribute approximately 65.7% of total purchases, indicating a high level of dependency and potential supply risk. 


Bulk Purchasing Impact

Larger purchase quantities were associated with significantly lower unit costs. Bulk orders showed around 72% lower unit prices compared to small orders, demonstrating clear economies of scale. 


**Inventory Performance**

The analysis identified about $2.71 million tied up in slow-moving or unsold inventory. Low turnover items increase storage costs and reduce available working capital. 



**Pricing and Product Performance**

A set of 198 products was identified with low sales but relatively high profit margins. These products may benefit from targeted marketing or pricing adjustments to increase demand without sacrificing profitability. 


Profitability Differences Across Suppliers

Lower-volume suppliers tended to operate with higher margins, while high-volume suppliers generated more revenue with lower margins. Statistical testing confirmed that these differences were significant, suggesting different operating strategies across supplier groups. 


**Key Findings**

- Heavy reliance on a small number of suppliers increases operational risk

- Bulk purchasing significantly reduces unit costs

- Slow-moving inventory ties up capital and increases holding costs

- Pricing strategy strongly influences profitability

- Some high-margin products suffer from low demand

**Recommendations:**

**Based on the analysis, the following actions could improve performance:**

-Diversify the supplier base to reduce dependency

-Review pricing for low-volume, high-margin products

-Adjust purchasing quantities for slow-moving items

-Use bulk purchasing strategically where demand is stable

-Improve marketing or distribution for underperforming products

**Tools Used**

Power BI for dashboard development and visualization

- Python (Pandas, NumPy) for data analysis

- SQL for data extraction and preparation

- Excel for data cleaning and preprocessing

**- Repository Contents**

- Power BI dashboard file (.pbix)

- Analysis report

- Supporting data and scripts

**Skills Demonstrated**

- Exploratory data analysis

- Business performance analysis

- Pricing and profitability evaluation

- Inventory analysis

- Data visualization

-Insight generation for decision support

**Author**

**Manish Kumar**

