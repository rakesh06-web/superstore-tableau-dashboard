# superstore-tableau-dashboard (Academic Project)
Interactive Tableau dashboard analyzing retail sales, profit, and discount impact | Tableau, Data Visualization 
# Retail Sales and Profitability Dashboard

Tableau dashboard analyzing profitability, discounting, and regional performance across 9,994 retail orders (2014-2017).

I built this dashboard to understand how a retail company performs across different products, locations, and customer segments. I wanted to find out which products generate the most profit, where the company loses money, and how discounts affect overall profitability.

The dashboard brings together five visualizations to make it easier to explore business performance.

**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/superstore-workbook/Dashboard1)

## What I Wanted to Find Out

- Which product categories and sub-categories generate the most sales and profit?
- Do higher discounts lead to lower profit margins?
- Which states perform well, and which have lower profitability?
- How do sales and profits change throughout the year?
- Which customer segments contribute the most to sales and profit?

## Dataset

I used the Sample Superstore dataset, which contains 9,994 records and 21 columns covering retail transactions from 2014 to 2017.

The dataset includes sales, profit, discounts, product categories, customer segments, locations, order dates, and shipping dates.

## Tools and Techniques

- Tableau Public
- Calculated fields for Profit Margin and Shipping Delay
- Trendline analysis
- Interactive year filter

## What's in the Dashboard

**1. Category and Sub-Category Performance**

This chart compares sales and profit across product categories and sub-categories. It helps identify products that generate strong sales but contribute less profit.

**2. Discount vs. Profit Margin**

I used a scatter plot with trendlines to examine how discounts relate to profit margins across product categories.

**3. Sales and Profit by State**

The map shows how sales and profit vary across U.S. states. It helps identify locations where the company performs well and areas where profitability is weaker.

**4. Monthly Sales and Profit Trends**

This chart tracks monthly sales and profit from 2014 to 2017. I added a year filter to make it easier to compare performance over time.

**5. Customer Segment Performance**

This visualization compares Consumer, Corporate, and Home Office customers to understand their contributions to sales and profitability.

## What I Found

**1. Product Performance**

Technology was the most profitable category, followed by Office Supplies. Furniture generated considerable sales but had lower profits than the other categories. Tables were one of the weaker-performing sub-categories.

**2. Discounts and Profit Margins**

Profit margins generally decreased as discounts increased. The trendlines suggested that margins declined more sharply around the 20% discount level, although this is an observed pattern rather than a confirmed cutoff.

**3. Regional Performance**

California and New York were among the strongest states in terms of profitability. Texas and Illinois showed weaker profit performance, which suggests that sales alone do not tell the full story of regional performance.

**4. Customer Segments**

The Consumer segment contributed the most sales, but Corporate customers had better profitability relative to their sales.

**5. Monthly Sales Trends**

Sales were generally higher in November and December, which suggests that seasonal shopping patterns influence retail performance.

## What I Would Recommend

- Review pricing and costs for Furniture products, especially Tables, to understand why their profits are relatively low.
- Take a closer look at higher discounts and check whether they are reducing profit margins.
- Investigate shipping costs, product performance, and discounting in states such as Texas and Illinois.
- Focus on retaining profitable Corporate customers while finding ways to improve margins in the Consumer segment.
- Plan inventory and promotions ahead of November and December to prepare for higher seasonal demand.

## Dashboard Screenshot

![Dashboard Overview](images/dashboard-overview.png)

## How to View the Project

Explore the dashboard using the Tableau Public link above. To view the workbook locally, download `superstore-workbook.twbx` from this repository and open it in Tableau Desktop or Tableau Public Desktop.

## What I Learned

This project improved my Tableau skills, especially creating calculated fields, building interactive dashboards, and comparing different business metrics.

The most important lesson was that high sales do not always mean high profits. Looking at discounts, product categories, customer segments, and locations together gives a much better picture of business performance than any single view.

## About Me

**Rakesh Boindla**

Master of Science in Information Systems
The Catholic University of America

GitHub: [rakesh06-web](https://github.com/rakesh06-web)
