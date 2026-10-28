# Olist E-Commerce Analysis

Analysis of about 100,000 orders from the public Olist e-commerce dataset, to find revenue drivers, delivery problems and customer retention opportunities.

**Question:** How can Olist grow beyond its current revenue of R$15.88M?

**Tools used:** Excel (data cleaning, formulas, PivotTables) and Power BI (modelling and dashboards)

**Data:** Olist e-commerce public dataset

## Data preparation
- Used Excel to clean and prepare the data, create formulas and calculated columns, build PivotTables and summaries, and check the data before loading it into Power BI.
- Created a `delivery_delay_time` column (actual delivery minus estimated delivery) to measure logistics performance.
- Removed canceled orders so the analysis covers completed transactions only.

## Key findings

**Financial performance**
- Total revenue: R$15.88M. Average order value: R$160.91.
- Top category: Health & Beauty, followed by Watches.
- Revenue peaks in November.

**Geography**
- The Southeast region generates 67% of revenue.
- São Paulo alone accounts for about 42% of sales volume.

**Delivery and customer satisfaction**
- Delivery days and review scores are strongly negatively correlated.
- About 92% of orders arrive on time, but the roughly 8,000 late orders account for most 1-star reviews.
- Office Furniture and Small Appliances are the most affected by delays.

**Customer retention**
- 97% of customers bought only once, and only about 3% returned for a second purchase.

## Recommendations
1. Renegotiate shipping for heavy items, such as furniture, in the Southeast to reduce late deliveries.
2. Run a second-purchase coupon campaign in Health & Beauty, the highest-volume category.

## Author
Comfort Udoh, Data Analyst
Email: comyj5@gmail.com
