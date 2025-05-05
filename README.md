# Supply-Chain-Data(Cosmetics analysis)
## Project Objective
I’ve been working on an extensive Excel-based project analyzing supply chain performance across product categories, shipping partners, locations, and suppliers within an e-commerce framework.

## Dataset used
- <a href="https://github.com/Naresh19-hub/Supply-Chain-Data-Cosmetics-analysis-/blob/main/supply_chain_data%20(cosmetics%20analysis).csv">Dataset</a>

## Questions (KPIs)
1️ Sales & Revenue Analysis
- Which product type generates the highest revenue?
- What is the average price of each product type?
- How do sales vary by SKU?
- Which products have the highest number of units sold?
- What is the relationship between price and sales volume? (Are expensive products selling more or less?)
________________________________________
2️ Inventory & Availability Analysis
- Which products frequently go out of stock?
- How do stock levels affect order quantities?
- What is the average lead time for restocking different products?
- Are there any products with long lead times but high demand?
- How does availability affect revenue generation?
________________________________________
3️ Customer Demographics & Behavior
- Which customer segments buy the most products? (e.g., age, location)
- Do customers in different locations prefer different product types?
- Is there a correlation between product price and customer demographics?
- Which products have the highest return or defect rates?
________________________________________
4️ Shipping & Logistics Performance
- What is the average shipping time for different locations?
- Which shipping carrier is the most cost-effective?
- Are there any patterns in delayed shipments?
- How do transportation modes affect delivery time and cost?
- What are the most common routes used for shipping?
________________________________________
5️ Manufacturing & Supplier Performance
- Which supplier provides products with the best availability and lead times?
- What is the average manufacturing lead time for different products?
- Which products have the highest defect rates after inspection?
- How do manufacturing costs compare across different suppliers?
- What is the relationship between production volumes and availability?

- Dashboard Interaction <a href="https://github.com/Naresh19-hub/Supply-Chain-Data-Cosmetics-analysis-/blob/main/Screenshot%202025-04-29%20172322.png">View Dashboard</a>

## Process
- In this project, I analyzed end-to-end e-commerce supply chain data to uncover insights on product performance, shipping efficiency, and supplier reliability. I used Excel tools like slicers, pivot tables, and charts to visualize key metrics such as lead times, defect rates, and delivery costs. The analysis helped identify improvement areas in logistics, inventory planning, and customer demand targeting.

## Dashboard
![Screenshot 2025-04-29 172322](https://github.com/user-attachments/assets/35c28687-3edf-4ec1-8f7d-2a4f10991b45)

# Project Insights
## Insights (Sales & Revenue Analysis)
1 Which product type generates the highest revenue?
- Skincare generates the highest revenue at ($ 241.6k )

2 What is the average price of each product type?
- The average prices by product type are: skincare ($ 31.95), haircare ($ 27.32), and cosmetics ($ 31.11).

3 How do sales vary by SKU?
- SKU10 generated the highest sales among all SKUs, indicating it is the top-performing product ( $996 )

4 Which products have the highest number of units sold?
- Skincare products have the highest number of units sold, totaling ($ 20.7k ) 

5 What is the relationship between price and sales volume? (Are expensive products selling more or less?)
- There is a very weak positive relationship between price and sales volume, indicating that expensive products are not significantly selling more.

## Insights (Inventory & Availability Analysis)
1 Which products frequently go out of stock?
- SKU78 (haircare) products most out of stock 

2 How do stock levels affect order quantities?
- there is very weak stock levels affect order quantites R square value is 0.1481

3 What is the average lead time for restocking different products?
- Skincare: Highest average lead time,
  Lead times vary by SKU, but most fall between 18 to 30 days, with several SKUs reaching the higher end (27–30 days), indicating a higher average lead time for this category.Haircare : Moderate average lead time ,
  Lead times are generally more balanced, ranging from 10 to 29 days, suggesting a moderate average lead time.Cosmetics : Lowest average lead time.This category tends to have slightly shorter lead times, mostly ranging from 15 to 26 days, indicating a lower average 
  lead time compared to skincare.

4 Are there any products with long lead times but high demand?
- Yes, several products such as SKU9, SKU14 (skincare), SKU12, SKU43 (haircare), and SKU35 (cosmetics) have both high demand and long lead times. 
  These products may face stockouts and require improved inventory planning or faster sourcing.

5 How does availability affect revenue generation?
- Availability has a minimal effect on revenue generation, as indicated by the very low R² value (0.0111). This suggests that higher availability does not strongly correlate with increased order quantities or revenue.

## Insights (Customer Demographics & Behavior)
1 Which customer segments buy the most products? (e.g., age, location)
- Female customers in Bangalore purchase the most products overall, especially in the haircare segment.
  Kolkata and Chennai also show high purchase activity, particularly for skincare and cosmetics, led by female and unknown demographics.

2 Do customers in different locations prefer different product types?
- Mumbai and Delhi prefer cosmetics the most.
  Kolkata and Chennai show a strong preference for skincare.
  Bangalore customers buy haircare products more than other types.

3 Is there a correlation between product price and customer demographics?
- there is very weak relationship between product price and customer demographics  is R square value 0.0049
  There is a very weak correlation between product price and customer demographics, as indicated by the low R² value of 0.0049. This suggests customer demographics do not significantly influence how products are priced or purchased.

4 Which products have the highest return or defect rates?
- Skincare products have the highest return or defect rates, with 40 inspection failures and a defect rate of 93.39%, indicating significant quality concerns.

## Insights (Shipping & Logistics Performance)
1 What is the average shipping time for different locations?
- Chennai has the highest average shipping time (6.00 days), while Bangalore has the lowest (5.28 days) among all locations.

2 Which shipping carrier is the most cost-effective? 
- Carrier B is the most cost-effective, offering the lowest average shipping cost (₹5.51) while handling the highest number of orders (2002).

3 Are there any patterns in delayed shipments?
- Carrier B (5.30) is the most reliable with the least delays, while Carrier A ( 6.14 ) shows a consistent pattern of longer delivery times.

4 How do transportation modes affect delivery time and cost?
- Road transport is the fastest, sea is the cheapest, and air offers a balanced option between cost and speed.

5 What are the most common routes used for shipping?
- Route B is the most commonly used with 2066 orders, followed by Route A (1844), and then Route C (1012), indicating that Route B is the primary shipping route based on order volume.

## Insights (Manufacturing & Supplier Performance)
1 Which supplier provides products with the best availability and lead times?
- Supplier 4 provides the best combination of highest availability (57.94) and low lead time (15.22) among all suppliers.

2 What is the average manufacturing lead time for different products?
- Haircare has the highest manufacturing lead time (17.06 days), followed by skincare (13.78 days) and cosmetics (13.31 days).

3 Which products have the highest defect rates after inspection?
- Skincare products have the highest defect rate after inspection (2.90%), followed by haircare (2.53%) and cosmetics (2.19%).

4 How do manufacturing costs compare across different suppliers?
- Supplier 4 has the highest average manufacturing cost (₹62.71), while Supplier 2 has the lowest (₹41.62) among all suppliers.

5 What is the relationship between production volumes and availability?
- The relationship between production volume and availability is very weak, as indicated by the very low R² value of 0.0025.

## Final Conclusion:
To Improve Overall supply chain data (Cosmetics Analysis)
1.Focus on Top Categories and SKUs
- Expand Skincare and Haircare SKUs: Skincare leads in both sales and revenue. Haircare also shows high demand in specific regions (like Bangalore).
  Use SKU10 as a model: Analyze SKU10's success (pricing, marketing, availability) and replicate those strategies for other SKUs.
2.Improve Inventory Management
- Prioritize high-demand SKUs: Especially skincare, haircare, and cosmetics with long lead times.
  Plan stock proactively: Since weak stock correlations exist, manual forecasting based on sale history is needed, not just stock levels.
  Avoid stockouts: Focus inventory planning efforts particularly on high-performing items.
3.Optimize Quality and Returns
- Fix skincare product defects: Since skincare has high return rates, tighten quality checks and supplier monitoring before final packing.
  Work closely with Supplier 4: They offer good availability and low lead times even if costs are higher — use them strategically for important products.
4.Strengthen Logistics and Delivery
- Use Carrier B whenever possible: They are the most reliable and cost-effective with the fastest deliveries.
  Improve shipping to Chennai: Focus on logistics improvements for Chennai, where delivery times are highest.
  Route B optimization: Since it's the most used shipping route, regularly monitor and negotiate better rates or faster service for this route.
5.Regional and Customer Strategy
- Target Bangalore females for haircare: Since they are strong buyers, focus marketing campaigns and discounts specifically for them.
  Demographics don't influence pricing: No need to create different pricing based on customer age/gender — focus pricing based on market behaviour only.
6.Manufacturing Improvements
- Speed up haircare production: It has the longest manufacturing times — maybe by working with faster suppliers or improving internal manufacturing processes.
  Balance manufacturing costs: Even if production cost is high (like for Supplier 4), if availability and quality are better, it can save losses later from stockouts and returns.

 
## Quick Summary Table for you:
- Area	Action
- Category Focus	Expand skincare and haircare high-performing SKUs
- Inventory	Prioritize high-demand SKUs with long lead times
- Quality	Reduce skincare defect rates
- Logistics	Maximize Carrier B usage, fix Chennai delivery delays
- Regional Targeting	Focus Bangalore haircare sales campaigns
- Manufacturing	Speed up haircare manufacturing and maintain skincare quality





  



