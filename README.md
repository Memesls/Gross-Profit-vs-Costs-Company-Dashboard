## Project Background 

Undisclosed company works in the advertisement and e-commerce industry. Working with many different e-commerce brands, they promote their products and sell them through storefronts, handling any refunds, gift cards, and shipping labels costs.

This project aimed to create a Power BI dashboard to visualize the store data regarding Gross Profit, Costs, and e-commerce Brand Performance from the years 2021 - 2024.

Insights and recommendations are provided on the following key areas:

- **Sales vs. Refunds**: This key indicator compares the sales of the company vs the refunds in the same periods.
- **QoQ and YoY growth**: This tracks the increase or decrease by quarter and year of the sales and refunds.
- **Brand performance**: An assessment of the overall performance of the multiple brands. This includes sales, refunds, and return rate by brand.
- **Shipping Costs**: An analysis of how much is spent on shipping returned items.
- **Gift Card Costs**: An evaluation of the total value of the redeemed gift cards and the reasons for issuing them.

The Dashboard aims to provide insight into the biggest culprits of money flowing out of the company and identify trends based on brands or dates.

## Data Structure

Data was collected from 3 different Shopify stores and 3 different Loop accounts (returns portal for clients) in the form of CSV files. They were later processed through Power Query and loaded into Power BI for analysis and data visualization. Below is a screenshot of the data model for this dashboard.

<br/>
<p align="center">
<img width="1232" height="720" alt="Screenshot 2025-07-23 194704" src="https://github.com/user-attachments/assets/d0187a50-fb6a-454d-a6a0-863d269fe1fa" />
</p>
<br/>

Before the start of the analysis and creation of visuals, a variety of checks were conducted for data familiarization. Each CSV file was evaluated in terms of data structure, data types, and possible connections to other data.

## Executive Summary

The analysis showed that the company experienced a considerable increase in sales with the creation of the new store "CBSD" in 2022. Although this brought a decrease in sales for the other 2 stores, it made up for more than double the numbers the other 2 stores were bringing in in the years 2023 - 2024. At the same time, refunds saw a similar increase, going from a steady 5% to around the 7% - 8% range of the sales total.

<br/>
<p align="center">
<img width="407" height="418" alt="Screenshot 2025-07-23 201703" src="https://github.com/user-attachments/assets/d46d8c9b-508d-4685-9eb6-82a38f45b666" />
</p>












Project explanation:

1. Filter the data needed from the Shopify stores
2. Download raw data in the form of CSV files
4. Identify key metrics and clean the data in Excel
5. Transform/Merge the data in Power Query
6. Create measures and visualizations in Power BI
