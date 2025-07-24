## Project Background 

Undisclosed company works in the advertisement and e-commerce industry. Working with many different e-commerce brands, they promote their products and sell them through storefronts, handling any refunds, gift cards, and shipping labels costs.

This project aimed to create a Power BI dashboard to visualize the store data regarding Gross Profit, Costs, and e-commerce Brand Performance from the years 2021 - 2024.

Insights are provided on the following key areas:

- **Sales vs. Refunds**: This key indicator compares the sales of the company vs the refunds in the same periods.
- **QoQ and YoY growth**: This tracks the increase or decrease by quarter and year of the sales and refunds.
- **Brand performance**: An assessment of the overall performance of the multiple brands. This includes sales, refunds, and return rate by brand.
- **Shipping Costs**: An analysis of how much is spent on shipping returned items.
- **Gift Card Costs**: An evaluation of the total value of the redeemed gift cards and the reasons for issuing them.

## Data Structure

Data was collected from 3 different Shopify stores and 3 different Loop accounts (returns portal for clients) in the form of CSV files. They were later processed through Power Query and loaded into Power BI for analysis and data visualization. Below is a screenshot of the data model for this dashboard.

<br/>
<p align="center">
<img width="1232" height="720" alt="Screenshot 2025-07-23 194704" src="https://github.com/user-attachments/assets/d0187a50-fb6a-454d-a6a0-863d269fe1fa" />
</p>
<br/>

Before the start of the analysis and creation of visuals, a variety of checks were conducted for data familiarization. Each CSV file was evaluated in terms of data structure, data types, and possible connections to other data.

## Executive Summary

The analysis showed that the company experienced a considerable increase in sales with the creation of the new store "CBSD" in 2022. Although this brought a decrease in sales for the other 2 stores in the years 2023 - 2024, the new store made up for more than double the numbers the other 2 stores were bringing. At the same time, refunds saw a similar increase, going from a steady 5% to around the 7% - 8% range of the total sales. Signaling that a deeper analysis is needed to find the root cause of this percentage increase and address it to effectively reduce costs. When it comes to shipping label costs per item, they have been consistently decreasing throughout the years. On the other hand, redeemed Gift card value has been increasing YoY. 

To summarize: 
- Sales increased considerably after the opening of the new store, but so did refunds, and to a higher degree percentage-wise. Possible culprits should include the brands with the most sales during that period. A deeper analysis is needed. 
- Shipping costs have seen a consistent decrease.
- Total gift card value has seen an increase of more than 100% since the new store opened.

## Dashboard Preview
<br/>
<p align="center">
<img width="1412" height="779" alt="Screenshot 2025-07-23 202155" src="https://github.com/user-attachments/assets/8ee4d8fa-4cd4-4bf6-b9b8-82e2b69670eb" />
</p>

<br/>
<p align="center">
<img width="1413" height="781" alt="Screenshot 2025-07-23 202207" src="https://github.com/user-attachments/assets/b6bfffe4-93ca-45de-a7fa-45f8e4c7d931" />
</p>


## Recommendations

1. Investigate which brands are responsible for the increase in refunds and gift cards. Once identified, confirm the reason for the returns/refunds. If it's due to faulty/damaged items, packages lost in transit, or shipment delays leading to cancellations, it's best to have a conversation with the brand directly and address the pain points our customers are experiencing.
   
2. Brands will be put in a probationary period. If they are unable to address the aforementioned pain points, they will be let go, independently of how much sales they bring in.



