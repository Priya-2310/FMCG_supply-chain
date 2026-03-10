📊 FMCG Supply Chain Service Level Dashboard
📌 Project Overview

This project analyzes service level performance in the FMCG supply chain for Atliq Mart using Power BI.

The objective of this project is to evaluate how effectively orders are delivered to customers by tracking key service metrics and comparing them against predefined business targets. The dashboard helps identify delivery delays, incomplete orders, and operational inefficiencies across cities, customers, and products.

🎯 Project Objectives

 * Analyze service level performance across the FMCG distribution network
 * Monitor delivery timeliness and order fulfillment accuracy
 * Identify delayed orders and incomplete deliveries
 * Highlight customer-level and product-level supply chain issues
 * Provide actionable insights to improve supply chain efficiency

📊 Key Metrics

The dashboard focuses on the following service level metrics:

**Metric	Description**
**OT % **(On Time)	Percentage of orders delivered on time
**IF %** (In Full)	Percentage of orders delivered with complete quantities
**OTIF %**	Orders delivered both on time and in full
**LIFR %	**Line Fill Rate
**VOFR %**	Volume Fill Rate

📈 Dashboard Features
## 🌐 Live Dashboard

View the interactive Power BI dashboard here:

https://app.powerbi.com/view?r=eyJrIjoiMGQ5MzAxZjAtY2VkOS00MWZlLWJhMjUtOGY5OTE0OTBjNTdhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=207c94a0c367bc805c68

The Power BI dashboard includes the following analytical views:

**Executive Overview**

* Service level KPI tracking
* Actual vs Target performance comparison
* City-wise service level performance
  
**Customer Performance**

* Customer service level matrix
* Conditional formatting based on performance gaps
* Top & Bottom customers by OTIF %

**Product Insights**

* Product-level fulfillment analysis
* LIFR and VOFR performance
* Sparklines showing product performance trends
* Trend Analysis
* Service level performance over time
* Dynamic metric switching
* Drill-down capability for detailed analysis

**Key Insights page**

* Summary of major findings
* Identification of supply chain inefficiencies
* Recommendations for improvement

📊 Key Insights

1. Overall OTIF performance is 29% vs target of ~66%, indicating major fulfillment challenges
2. Delayed deliveries significantly impact customer service levels
3. Some customers show extremely low OTIF performance, indicating potential service risks While VOFR is high (~96%), LIFR is much lower (~66%), indicating line-level fulfillment issues

🛠 Tools & Technologies

Power BI

DAX (Data Analysis Expressions)

Data Modeling (Star Schema)

Conditional Formatting

Interactive Data Visualization

📂 Dataset

The dataset includes the following tables:

fact_order_lines

fact_orders_aggregate

dim_customers

dim_products

dim_date

dim_targets_orders

These tables were modeled using a Star Schema to optimize analytical performance.
![fmcg model view](https://github.com/user-attachments/assets/2aeef056-1513-44a7-b476-35dea58dd4da)


📸 Dashboard Preview
Executive View
![fmcg 1](https://github.com/user-attachments/assets/6492d2aa-867a-4fd6-9107-64689fb29780)

Customer Performance
![fmcg 2](https://github.com/user-attachments/assets/a2602b22-5d13-4240-83eb-cb0e87bbb819)

Product Insights
![fmcg 3](https://github.com/user-attachments/assets/f88e4aea-fe5d-44be-ad21-59c2ad1c34a0)

Key Insights Page
![fmcg 4](https://github.com/user-attachments/assets/be903cca-6161-4e36-a9e0-8e09f40e2c74)


🚀 Skills Demonstrated

Power BI dashboard development

Data modeling and relationship design

DAX measure creation

KPI performance analysis

Business insight generation

Data storytelling for decision-making

📌 Conclusion

This dashboard provides actionable insights into service level performance within the FMCG supply chain. By analyzing OTIF, LIFR, and VOFR metrics across cities, customers, and products, the dashboard helps identify delivery inefficiencies and fulfillment gaps. These insights can support data-driven decision-making to improve operational efficiency and customer satisfaction.

👤 Author

Priyanka Lokkoju
Aspiring Data Analyst | Power BI | SQL | Data Visualization

⭐ If you found this project useful, feel free to star the repository!
