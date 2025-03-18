# Project Background 
Brosano Essentials Store, founded in 2020, is a retail company that specializes in a wide range of workspace supplies, from office furniture, supplies, to technology products, serving customers across the United States. The goal of this project is to investigate the performance of its sales data in order to surface recommendations for the product and sales team.  

Insights and recommendations are focused on the following key areas:
- Analysis of Sales Trends and Growth Rates
- Evaluation of Product Performance
- Insights into Customer Segmentation and Regional Sales

## Executive Summary
### Overview of Findings
Brosano Essentials has shown strong revenue growth over four years, with seasonal peaks in September and November, but struggles with declining new customer acquisition despite improving retention rates. While Phones and Chairs drive high sales, Tables and Bookcases remain unprofitable, requiring further investigation. Regionally, the West leads in revenue, while the East shows steady growth, presenting opportunities for targeted expansion.

### Data Structure & Initial Checks
The company's main database structure as seen below consists of four tables: Orders, Products, Customers, and Location, with a total row count of 9994 records. A description of each table is as follows:

![Data Flow Diagram Whiteboard in Dark Yellow Light Yellow Black Monochromatic Style (1)](https://github.com/user-attachments/assets/8ef18638-c061-45e6-bd56-a497aa8a1f84)

The interactive dashboard can be found [here](https://public.tableau.com/views/BrosanoEssentialsSalesDashboard/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## Insight Deep Dive
### Sales Trends and Growth Rates
- Between 2020 and 2023, Brosano Essentials processed an average of 2,500 orders annually, generating approximately $575K in revenue each year, with an average order value (AOV) of $231 per order.
- While total revenue dipped by 3% in 2021 compared to 2020, the sales rebounded with a 29% increase in revenue in 2022. This upward trend continued in 2023, with a 20% rise in revenue from the previous year, marking 2023 as the highest revenue year to date.
- March 2020 saw the highest growth rate, with a 1,132% surge in sales, accompanied by a 261% increase in AOV and a 241% rise in order count. This spike is likely tied to the initial impact of the pandemic. 

![YoY Analysis and Growth Rates](https://github.com/user-attachments/assets/a91ada40-7313-4331-a981-5f14ba9102bd)

### Seasonality
- Sales exhibit a clear seasonal pattern, with peak periods occurring in September and November, likely driven by back-to-school shopping, Black Friday promotions. November 2023 recorded the highest sales and order volume, showing the significant impact of seasonal promotions. 
- Additionally, March showed a notable sales spike too, suggesting a secondary seasonal trend. In contrast, January and February saw the lowest sales, reflecting the typical post-holiday slowdown in consumer spending.

![YoY Value and Growth Rate](https://github.com/user-attachments/assets/5cb2afa9-74cf-4e3d-941b-5b5173d9bf85)

### Product Performance
- Top selling items show a dip in 2021, including Binders, Chairs, Machines, Phones, Storage, and Tables. The dip might require closer analysis. Copiers, Accessories and Appliances gained traction post-2020, signaling increased demand.
![Product subcategory YoY Analysis](https://github.com/user-attachments/assets/70e096ce-9701-4ff0-b793-320d3c39483f)

- Phones ($330K) and Chairs ($328K) lead sales, both combined driving 28% of total sales and 25% of profits. While Tables (-$17.7K) and Bookcases (-$3.4K) are unprofitable despite strong revenue. 
- Machines ($1,646 AOV) and Copiers ($2,199 AOV) being the lowest order count products generate relatively high revenue due to their high AOV. In contrast, Binders (1,523 orders) and Paper (1,370 orders) are high-volume and contribute a smaller share of total revenue. This suggests they might be bought in bulk but at lower price points.
- Fasteners, Labels, and Envelopes contribute <2% of total sales, suggesting low demand or poor marketing. Furnishings and Art show small but stable growth, implying a niche market opportunity.

![Product Analysis](https://github.com/user-attachments/assets/88bf34fb-2e2e-48a3-b5ed-a167f589dca1)

### Customer Segmentations
- Over the past four years, Brosano has acquired 793 customers in total. The number of new customers is dropping sharply each year, showing a struggle in attracting new customers.

![new customer acquisition](https://github.com/user-attachments/assets/a40449f7-abfc-4530-94d0-4a26994bb157)
- Despite  declining new customer growth, repeat rate has risen from 73% in 2020 to 86% in 2023. This suggests strong customer loyalty once they are acquired. 
![customer behavior YoY](https://github.com/user-attachments/assets/1356791d-5537-4017-b1b9-0bc56f33567d)

### Regional Sales Analysis
- Over the four-year period, the West region has the highest revenue overall, with sales peaking at $250K in 2023. The market contributes 31.6% of total sales.
- East is the only region with steady sales growth of an average 18% growth per year from 2020 to 2023, increasing from $128K in 2020 to $212K in 2023. This steady increase might suggest strong market demand, customer retention, or marketing in the region. 
- Sales in the Central region fluctuates over time but showed a 43% increase in 2022 compared with 2021, and a 0.22% dip in 2023.
- The South region had the lowest total sales with $400K in four years and experienced a sharp decline in 2021 with only $76K revenue, making it the lowest sales recorded across four years and four regions. However, the sales showed a growth ever since with 26% increase in 2022 and 28% increase in 2023.

![regional sales value](https://github.com/user-attachments/assets/4974b31d-7973-47f3-b4fc-d283eb16e1f9)
![regional sales trends](https://github.com/user-attachments/assets/65290051-a87b-478c-8660-bf7818e112e0)

## Recommendations and Next Steps 
### Recommendations 
**Capitalize on seasonal trends and Optimize promotion campaigns**: 
- Ensure sufficient inventory is prepared ahead of time for September and November using historical data and forecasting the demand for accuracy. March requires a deeper analysis of sales drivers. 
- Conduct a deep analysis of past promotions to assess their effectiveness. 
- During the off-season months in January and February, consider promoting essential and consumable products such as Papers or Binders, through email to encourage re-engagement, or testing new product lines to boost revenue. 

**Product Portfolio Optimization**
- Reevaluate sourcing costs and pricing strategies for unprofitable items like Tables and Bookcases. 
- Consider bundle lower AOV items with high AOV products to increase recurring revenue.
- Introduce a diversified product selection in areas where demand is growing to attract existing customers with more options.

**Customer Acquisition & Retention**:
- Since repeat purchase rates increased YoY, prioritize programs to strengthen retention. Consider launching loyalty programs, exclusive discounts, or subscription models. 
- The dataset lacks customer acquisition source data, making it impossible to evaluate Customer Acquisition Cost (CAC). To better understand the effectiveness of acquisition strategies, capturing acquisition source data is recommended for further analysis. 

**Regional Sales**
- Since West market leads the revenue and East market shows a steady growth, ensure stable supply in these regions. Introduce loyalty program to keep them engaged.
- Growth has fluctuated over the years in Central. Consider further market research for the trend and customer purchasing patterns. 
