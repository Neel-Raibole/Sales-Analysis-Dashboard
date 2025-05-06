# Sales Analysis Dashboard – TechWorks USA

## Problem Statement  
TechWorks USA, a national retail and distribution company, lacked a consolidated view of sales performance and market penetration across its U.S. operations. Without a clear understanding of regional dynamics and customer behavior, leadership struggled to align on strategic priorities and identify areas needing attention or investment.

## Objective  
The Sales Analysis Dashboard was developed to provide a unified, high-level view of key sales metrics Revenue, Profit, Orders, Returns, and Customer Activity over a rolling 6-month window. The primary goal was to identify underperforming regions, diversify market focus, and empower cross-functional teams in Sales, Product, Marketing, and Customer Acquisition with actionable insights.

The dashboard is powered by order-level transactional data organized in a star schema model, with fact and dimension tables covering geography, product, customer, and returns. It enables leadership to view trends at the national level while also drilling down to specific regions, states, and cities for targeted analysis and tracking of ongoing improvements.

## Executive Summary  
The Sales Analysis Dashboard offers TechWorks USA’s leadership a comprehensive, rolling 6-month view of key performance indicators Sales, Profit, Orders, Returns, and Customer Trends at national and drill-down levels. Analysis reveals that the East and West Coasts drive two-thirds of revenue, with Office Supplies leading order volumes but Technology delivering stronger margins. Seasonal volatility is evident, with a sharp sales dip in December and profit compression in November despite heavy discounting. Returns surged 157% from July to December especially in Los Angeles eroding profitability, while customer growth peaked in September before plateauing.

To address these insights, the dashboard supports targeted initiatives: geographic diversification into underpenetrated regions, refined seasonality forecasting, margin preserving promotions, furniture-category cost realignment, returns-management improvements, and scaling proven customer-acquisition tactics.

---

## Dashboard Overview

![Landing Page Dashboard](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20LP.jpg)
![Sales Dashboard](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20SDB.jpg)
![Profit Dashboard](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20PDB.jpg)
![Orders Dashboard](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20ODB.jpg)
![Orders Returned Dashboard](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20ORDB.jpg)
![Customer Dashboard](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20CDB.jpg)

---

## Insights Deep Dive  
All insights are based on a rolling 6-month analysis. Screenshots are referenced alongside each insight replace placeholders with your actual image paths.

### 1. Overall Market Dynamics  
The U.S. East and West Coasts together drive approximately 66.7% of total sales (East: $163.3K, West: $154.2K), and this dominance repeats across orders, profits, returns, and customer counts. Such concentration underscores the need to diversify beyond coastal markets to reduce exposure to regional swings.

![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%201%20-%201.jpg)

### 2. Sales Insights  
- **Steady Growth with Seasonal Dips:** Sales climbed roughly 40% month-over-month, peaking at $118K in November, before dropping 11% in October and plunging 28% in December (from $118K to $84K). The December drop may reflect year-end inventory clearance or holiday related supply constraints.  
- **Segment Drivers:** In the East and Central regions, Technologies lead sales, followed by Technology and Furniture. Conversely, the West and South favor Office Supplies, then Office Supplies and Furniture.

![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%202%20-%201.jpg)
<p align="center">
  <img src="https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%202%20-%202.jpg" alt="IDD 1 - 1" width="500"/>
  <img src="https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%202%20-%203.jpg" alt="IDD 1 - 2" width="500"/>
</p>

### 3. Profit Insights  
- **Margin Plateau with Spikes:** Profit stabilized around $9.5K/month, peaking in September likely driven by elevated order volumes but experienced two sharp declines: ~16% after September’s peak and ~13% in December (from $9.7K to $8.4K).  
- **Decoupling in November:** November saw a 51.2% surge in sales but only 4% profit growth, suggesting discounting or cost pressures.  
- **Product-Line Profitability:** Office Supplies and Technology show comparable margins, while Furniture lags significantly and even generated negative profit in October indicating that furniture was sold below cost.

![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%203%20-%201.jpg)
![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%203%20-%202.jpg)

### 4. Order Insights  
Order volumes mirror sales trends closely. Office Supplies account for over 50% of all orders, despite Technology driving higher profitability highlighting an opportunity to apply Office Supplies’ successful order generation tactics to more lucrative product lines.

![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%204%20-%201.jpg)
![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%204%20-%202.jpg)

### 5. Returns Insights  
- **Rising Return Rate:** The return rate averaged 6.5%, but grew 157% from July through December.  
- **Geographic Hotspot:** While New York leads in sales and orders, Los Angeles exhibits the highest returns, pointing to potential regional fulfillment or product fit issues.  
- **Profit Impact:** Months with elevated returns align with lower profits, confirming the negative drag of returns on overall profitability.

![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%205%20-%201.jpg)
![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%205%20-%202.jpg)

### 6. Customer Insights  
- **Acquisition Surge & Retention Plateau:** Active ordering customers rose from 102 in July to 196 in September, then plateaued with a dip in October. This suggests that September’s acquisition tactics were particularly effective, while subsequent months maintained retention but failed to sustain new growth.  
- **Segment Value:** Consumers represent 51.3% of customers, Corporate 29.7%, and Home Office 19%, indicating the strongest loyalty among retail buyers but also a chance to grow B2B segments.

![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%206%20-%202.jpg)
![alt text](https://github.com/Neel-Raibole/Sales-Analysis-Dashboard/blob/main/Dashboard%20Images/IDD%206%20-%201.jpg)

---

## Recommendations  

### 1. Broaden Geographic Reach  
With over two-thirds of sales concentrated on the East and West Coasts, developing targeted growth initiatives in underpenetrated regions such as the Midwest and South will reduce geographic risk and unlock new revenue streams. Consider localized promotions, partnerships with regional distributors, and tailored marketing campaigns to build presence beyond coastal strongholds.

### 2. Enhance Seasonal Demand Planning  
The pronounced dips in October and December underscore the need for more sophisticated seasonality adjustments. Integrate holiday calendars and historical trend analysis into demand forecasts and proactively align inventory and promotional activities to smooth out sales volatility during these months.

### 3. Refine Pricing and Promotion Strategies in Peak Months  
November’s 51% sales surge coupled with only 4% profit growth suggests heavy discounting or cost overruns. Conduct a margin impact analysis of past promotions to identify which discount levels still deliver profitable growth, and adopt more targeted offer structures that boost revenue without eroding margins.

### 4. Leverage High-Order Segments to Boost Profitable Lines  
Office Supplies generate over half of all orders but offer slimmer margins compared to Technology. Reverse engineer the marketing and merchandising tactics that drive Office Supplies’ order volumes such as bundling or subscription models and apply these to higher-margin categories like Technology and Furniture.

### 5. Address Furniture Profitability Gaps  
Consistent negative or low margins in Furniture indicate possible underpricing or elevated costs. Perform a cost-to-serve analysis on furniture SKUs, renegotiate supplier terms where feasible, and explore value added services (e.g., in-home setup) that justify premium pricing and improve profit contribution.

### 6. Strengthen Returns Management in High-Return Markets  
Los Angeles’s elevated return rates are eroding profitability. Implement a root cause evaluation of return reasons (e.g., product damage, fit issues, fulfillment errors) and deploy corrective actions such as improved quality checks, enhanced packaging, or clearer product descriptions to reduce reverse logistics costs.

### 7. Replicate Successful Customer Acquisition Tactics  
September saw stellar customer growth that wasn’t sustained in subsequent months. Conduct a post-mortem of the marketing channels, messaging, and offers used in September, and scale the most effective elements into Q4 campaigns to reignite new customer acquisition while maintaining retention.

### 8. Cultivate B2B and Home-Office Segments  
Consumers dominate at 51.3% of customers, leaving significant upside in Corporate (29.7%) and Home Office (19%) segments. Develop segment specific value propositions such as volume discounts, dedicated account support, or bundled service offerings to diversify the customer base and enhance revenue resilience.

---

## Tech Stack  
- PowerBI  
- Excel  
