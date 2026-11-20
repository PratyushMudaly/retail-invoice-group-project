# Retail Invoice Analytics: Power BI Dashboard

Group project by **Pratyush Mudaly, Ashish Kumar Das & Subhashish Nanda**, built on an **AI-generated retail invoice dataset**.

## Overview
Interactive Power BI dashboards that analyze retail invoice data to understand sales, discounts, campaigns, regional performance, and returns.

## Business Questions
1. How do discount levels affect sales, quantity and profit?
2. Which campaigns generate better sales and customer engagement?
3. Do combo purchases increase basket size and order value?
4. Which regions and cities perform best?
5. What is the impact of returns and cancellations on revenue?
6. How does excessive discounting affect profit?


## KPIs
| Total Sales | Total Profit | Profit Margin | Invoices | Customers | Quantity |
|---|---|---|---|---|---|
| 39.98M | 8.93M | 0.22 | 575 | 364 | 2,419 |


## Key Findings
- The **10-20% discount band** gives the highest sales, quantity and profit.
- The **20%+ discount band** gives the lowest sales and profit, even with a 22.5% margin.
- **Regular Sale** leads in sales and invoices; **Diwali Mega Sale** has the highest average order value.
- **Combo purchases** have a higher average order value (₹93,811 vs ₹78,762) and larger baskets (4.70 vs 3.29 items).
- **Karnataka** is the top state; **Vijayawada** is the top city.
- **Electronics** has the most returned orders; **Home** has the most cancelled orders.


## Dashboard Preview

### Overview
![Overview](RETAIL_INVOICE%20POWER%20BI%20%28GRP%20PROJECT%29/RETAIL_INVOICE%20SCREENSHOT/overview.png)

### Discount & Profitability
![Discount](RETAIL_INVOICE%20POWER%20BI%20%28GRP%20PROJECT%29/RETAIL_INVOICE%20SCREENSHOT/discount.png)

### Campaign & Basket Analysis
![Campaign](RETAIL_INVOICE%20POWER%20BI%20%28GRP%20PROJECT%29/RETAIL_INVOICE%20SCREENSHOT/campaign.png)

### Regional Performance
![Regional](RETAIL_INVOICE%20POWER%20BI%20%28GRP%20PROJECT%29/RETAIL_INVOICE%20SCREENSHOT/regional%20.png)

### Returns & Cancellations
![Returns](RETAIL_INVOICE%20POWER%20BI%20%28GRP%20PROJECT%29/RETAIL_INVOICE%20SCREENSHOT/returns.png)


## Conclusion & Recommendations
- Keep most discounts in the **10-20% range**, which gave the highest sales and profit.
- Review **20%+ discounts**: they bring low volume, and margins are about the same as in other bands.
- Promote **combo offers**, since they lead to higher order value and larger baskets.
- Learn from the **Diwali Mega Sale** (highest average order value) and use it in other campaigns.
- Focus on top states such as **Karnataka**, and investigate low performers such as **Uttarakhand**.
- Reduce **cancellations (Home, Fashion)** and **returns (Electronics)**.


## Limitations & Future Improvements
- The dataset is AI-generated, so findings are for practice, not real business decisions.
- Future work: add a date or month trend analysis, customer segmentation, and a profit forecast.
  

| Member | Contribution |
|---|---|
| ⭐ **Pratyush Mudaly** | **Designed the visualizations and dashboard pages, and extracted the business insights** |
| Subhashish Nanda | Data cleaning and transformation in Power Query, and created the project presentation (PPT) |
| Ashish Kumar Das | Data modelling and DAX measures |
## Tools Used
Power BI, Power Query, DAX

## Project Files
All files are inside the folder `RETAIL_INVOICE POWER BI (GRP PROJECT)`:
- `.pbix` dashboard file (open it in Power BI Desktop )
- `DATA SOURCE`: the dataset (Excel)
- `PPT AND PDF`: the project presentation (one `.pdf` and one `.pptx`)
- `RETAIL_INVOICE SCREENSHOT`: dashboard images

## Note
The dataset was generated using AI for practice and learning purposes. It is not real company data.







