# FestMan-Stores-Analysis-Sales-Report
Financial Analysis Sales Report
Dashboard-1
<img width="1345" height="743" alt="Screenshot 2025-08-30 140442" src="https://github.com/user-attachments/assets/d52468c3-9663-426a-8f77-b50ac1190179" />
Dashboard-2
<img width="1340" height="746" alt="Screenshot 2025-08-30 140514" src="https://github.com/user-attachments/assets/5ac7d99d-bc0c-416c-8221-765b2abf672a" />

𝗙𝗲𝘀𝘁𝗠𝗮𝗻 𝗦𝘁𝗼𝗿𝗲𝘀 𝗔𝗻𝗻𝘂𝗮𝗹 𝗼𝗳 𝟮-𝘆𝗲𝗮𝗿 𝗿𝗲𝗽𝗼𝗿𝘁.
𝗙𝗶𝗻𝗮𝗻𝗰𝗶𝗮𝗹 𝗦𝗮𝗹𝗲𝘀 𝗥𝗲𝗽𝗼𝗿𝘁𝘀 𝗮𝗻𝗱 𝗗𝗮𝘀𝗵𝗯𝗼𝗮𝗿𝗱𝘀


## Part 1: Company Overview and Goal

Festman Store is a mid-sized retail chain specializing in consumer goods, including electronics, home essentials, and fashion products. The store operates across multiple regions and serves a diverse customer base. With increasing competition in the retail sector, Festman Store seeks to leverage data-driven insights to monitor sales performance, identify growth opportunities, and optimize inventory and promotions.

### Business Goals:
Business Problem:
The festman sales wants to know the current vs the previous year’s growth, total sales compared to last year, profit margin difference, which segments contribute more and less, which products are sold the most, etc. Which country market has more potential or higher to lower sales, and they want to optimize their inventory sales and increase profitability in target regions, and optimize the market expenditure.

### Business Problem:
The Festman sales wants to know, potential customers and regions, the current vs the previous year’s growth trend, total sales compared to last year, profit margin difference, and the company has growing sales across multiple countries and segments, but profit margins are under pressure due to rising costs and heavy discounting. Management wants to identify which products, segments, and countries are truly profitable, evaluate the impact of discounts on profit, and optimize the sales strategy to maximize sustainable growth.

1. Maximize Profitability, 2. Optimize Discount Strategy, 3. Identify High-Value Segments, 4. Product Portfolio Management, 5. Regional / Country Performance, 6. Sales Forecasting & Seasonality, 7. COGS Optimization
---

## Part 2: Dataset Overview
Excel data sources, data type xlsx, data contains 1 Sales table with 15 columns loaded into Power BI, and transformed it through ETL, cleaned data, inconsistencies, removed null values, invalid formats, extracted Year, etc. The tools used are Power BI and Excel. 

### Table Fields:
  Sales Table and Date 
- Segment (Channel Partners, Government, Midmarket, Enterprise, Small Business)  
- Country (Canada, France, Germany, Mexico, USA)
- Product (Amarilla, Carretera, Monatana, Paseo, Velo, VTT)  
- Discount Band (HighLow, Medium)  
-  Units Sold, Manufacturing Price, Gross Sales, Discounts, Net Sales, COGS, Profit
   
The dataset spans from **2013 to 2014**, enabling detailed month-over-month and year-over-year analysis.

---

## Part 3: Analytical Framework

### Supporting Metrics:
- Number of Orders  
- Average Order Value (AOV)  
- MoM Growth %  
- YoY Comparison  

### Key Dimensions:
- Time (Month-Year)  
- Product Category    
- Channel and Store Location  

### Analysis Objectives:
- Understand revenue trends over time  
- Analyze category-level performance  
- Measure Month-over-Month (MoM) and Year-over-Year (YoY) growth  
- Assess performance across customer segments and sales channels  
- Derive insights to guide promotional strategy, budget allocation, and inventory planning

---

## Part 4: Summary Recommendations

Based on the insights derived from the 2022–2023 dataset, here are high-level recommendations aligned with the business goals:

- **Stabilize February Performance:** Launch retention or loyalty campaigns in late January to avoid revenue loss during seasonal dips.
- **Capitalize on Strong Categories:** Invest in Personal Care and Household during Q2 and Q4 as they consistently show peak performance.
- **Enhance Online Experience:** With online revenue outpacing in-store, focus on digital UX, personalization, and exclusive online deals.
- **Refine Membership Strategy:** Convert declining Regular members into VIPs with structured loyalty incentives.
- **Target 18–45 Age Group:** Tailor product placements and marketing campaigns toward younger and mid-career consumers who showed the most growth.

---

## Part 5: Country-Wise 
### Canada
In profit margin by segment, Canada at the 1st Channel partners at the top, on 2nd Midmarket and government 26.62% but Enterpirse is in minues except Montana product, means performed bad, 16.5% profit margin, discount offered by discount band, low 7.79%, medium 31.88%, high 60.33%, sales amount increased over the year, paseo, amarilla, VTT top products, profit margin current year in minus due enterprise in negative, profit margin 16.0%.

### France
Top 3 products: Paseo, Amrilla, Velo sales over the period high, profit margin by segment Channel partners, Midmarket and Government on top, but in the enterprise segment, except VTT, all products in minus by profit margin, discount low 8.98%, medium 42.51%, high 48.51%, profit margin in minus 18.3% 

### Germany
Profit margin by segment same as above, but all enterprise products are in minus due to enterprise, and sales amount is declining, top products are paseo, vello, amarilla, discount band low 20.35%, medium 31.24%, high 48.41%, profit margin current year is in minus due to enterprise, profit margin 17.4%
### Mexico
Profit margin by segment as above, but enterprise, except Montana all products in minus, Top products paseo, VTT, amarilla, sales by month slightly decrease, profit margin current year in plus, profit margin 16.7%.

### USA
VTT, 13.45% profit margin, discount 557k, 35k orders, 4.82 COGS, Over the years, good sales. Profit margin by segment same for Channel Partners, Midmarket, and Government, but the enterprise is in the minus, including all products in the enterprise performed badly. top 3 products Paseo, Velo, VTT, profit margin 14%, discount by band low 7.09%, medium 24.04%, high 66.87%, profit margin is in plus


### Good and Bad performing Products
In Canada, Velo is not performing well, reducing discounts or optimizing strategy, and Paseo Amarilla VTT is performing well.

In France, Top 3 products: Paseo, Amarilla VTT, sales over the period static, profit margin by segment same as above, but in the enterprise segment, except VTT, all products in minus by profit margin, discount low 8.98%, medium 42.51%, high 48.51%, profit margin in minus, 18.4%.

In Germany, 2013, except for November, all months had high sales, and in 201,4, except January, March, and November, all months had good sales with 18.56% profit margin.
Profit margin by segment same as above, but all enterprise products are in minus, and sales amount is declining, top products are paseo, vello, amarilla, discount band low20.35%, medium 31.24%, high48.41%, profit margin current year is in minus. 
In Germany, paseo has the highest discount among all products, a low profit margin, the highest COGS, and contributes 36%. Here, there is a huge loss, maybe high sales due to the discount offered, but low profit

In Mexico, the Profit margin by segment is as above, but enterprise, except for Montana, all products are in minus. The Top products are paseo, VTT, and amarilla. Sales by month slightly decrease, profit margin current year is plus, profit margin 16%.
Paseo and Velo are performing badly. For VTT and Montana, performing well high profit margin needs more discount offers. You can shift the discount from Paseo and Velo to Montana and VTT.
In Mexico, paseo has a 36% contribution but a very high discount, low profit margin, high COGS, and needs to reduce discount and optimize pricing. Also, for velo, the profit margin is 8% very low, and a high discount needs to be optimized.

In the USA, Velo needs a proper pricing strategy and to reduce discounts because it has the lowest profit margin among all the countries and products. Paseo has a high discount, but the profit is very high.
Canada, France, and Germany had negative profit margins due to the enterprise in 2014, while 2014 Mexico and the USA had positive.

In Germany, paseo has the highest discount among all products, a low profit margin, the highest COGS, and contributes 36%
Here, there is a huge loss, maybe high sales due to the discount offered, but low profit

Enterprise Segment is making a loss because in Canada, France, and Germany, it has negative profit margins.
We can reduce discounts where excessive and profit margin is low, then we can optimize that discount to offer those products and regions where higher profit margins and sales.


---


### Recommendations:
- **Stabilize February** with early Q1 promotions or loyalty pushes to avoid simultaneous drops in both volume and value.
- **Leverage high-AOV months** (like **July and November**) to introduce premium product bundles or upsell offers.
- Use insights from **November’s high-AOV behavior** to build **holiday season strategies** that focus on value per customer, even if volume is lower.
- Tailor marketing to monthly AOV patterns — deploy **basket-size incentives** during low-AOV periods and focus on **premium promotions** during high-AOV months.
---


### Recommendations: Product-Wise
For Enterprise segment has a -3.00% average negative profit margin in almost all products. 
It needs.

  1. Revisit Pricing & Discount Policy
- Review contract terms with enterprise clients; current discount levels may be unsustainable.
- Offer targeted discounts (only to specific regions/segments with low demand)
- Introduce tiered discounts (higher discounts only if volume targets are exceeded).
- Test smaller discount tiers to see if sales volume remains stable.
  
  2.  Cost Optimization
- Negotiate bulk production or supplier deals specifically for enterprise orders.
- Streamline logistics/operations to cut down COGS for this segment.
  
  3. Value-Added Offerings
- Instead of giving pure discounts, offer value-added services (extended warranty, premium support, faster delivery) to maintain competitiveness without hurting margins.

  4. Product Positioning
- If customers only buy it when discounted, maybe it’s a commodity product.
- The company can decide: either keep it as a loss-leader (to attract buyers into buying other items) or reposition it.
  
  5. Operational Action
- Negotiate better deals with suppliers to lower Manufacturing costs.
- Explore efficiency in production to reduce COGS.
  
  6.Bundle / Upsell Strategy
- Bundle the product with higher-margin items.
- Promote cross-selling to increase total basket value.
  
  7. Improve Pricing Strategy
- Check if the Manufacturing Price is too close to the Sale Price after discount.
- Consider increasing the base Sale Price slightly, then offering smaller discounts


