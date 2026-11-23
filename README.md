# Brazilian E-Commerce Analysis — Power BI Mini Project

A small, hands-on Power BI project created to practise building an interactive business dashboard and communicating basic business insights from Brazilian e-commerce data.

This is a learning project, not a production BI solution. Its scope is intentionally limited to the dashboard and the short analysis presentation included in this repository.

## Project files

```text
powerbi-brazilian-ecommerce-analysis/
├── powerbi/
│   └── Dashboard_PP_Brazilian.pbix
├── report/
│   └── Brazilian-Ecommerce-Analysis-2018.pdf
├── assets/
│   └── report-preview.png
└── README.md
```

- **Power BI file:** Open `powerbi/Dashboard_PP_Brazilian.pbix` in Power BI Desktop to explore the report and its data model.
- **PDF report:** `report/Brazilian-Ecommerce-Analysis-2018.pdf` contains the eight-page presentation that accompanies the dashboard.
- **Preview:** `assets/report-preview.png` provides a visual overview of the PDF presentation.

## Dashboard scope

The supplied PBIX contains one report page named **OVERVIEW**. It includes:

- KPI cards for Total Revenue, Order Count, Average Order Value (AOV), and Delivered Customers.
- A time-trend visual for comparing selected business measures over time.
- A year slicer and quarter slicer.
- A dynamic measure selector used by the trend visual.
- An order-status donut chart.
- Revenue by product category.
- Order count by customer city.

The Power BI model includes tables for orders, order items, customers, sellers, geolocation, payments, reviews, products, and product-category name translation, along with supporting date and measure tables.

## Business questions explored

The accompanying presentation discusses:

1. How did overall revenue, order volume, delivered customers, and AOV perform in the 2018 overview?
2. How did selected business measures change over time?
3. Which product categories contributed the most revenue?
4. Which cities contributed the most orders?
5. What does the order-status distribution suggest about fulfillment performance?

## Selected observations from the submitted presentation

The following are observations stated in the accompanying PDF; they are reproduced here as the original project's reported findings, not independently re-audited calculations:

- The report states that revenue, order count, and delivered customers increased by around 20% or more compared with the prior-year values displayed in its KPI cards.
- AOV is shown as slightly lower than the prior-year value, leading the presentation to interpret growth as more volume-driven than basket-value-driven.
- Health & Beauty, Watches, Bed Bath, Sports, and Computers are identified as leading revenue categories.
- São Paulo is identified as the largest city by order count, followed by other major cities including Rio de Janeiro and Belo Horizonte.
- The presentation reports that delivered orders account for 98.16% of total orders.

For exact figures and the original commentary, refer to the PDF presentation.

## Tools and concepts practised

- Microsoft Power BI Desktop
- Report layout and visual design
- KPI cards and time-series visuals
- Slicers and interactive filtering
- Category and geographic analysis
- Order-status / fulfillment analysis
- Basic business interpretation and recommendations

## Learning context

This mini project was completed as a practical exercise in learning how to build a Power BI report. The main goal was to become familiar with arranging visuals, selecting measures, applying filters, and explaining what the dashboard shows.

The project reflects an early stage of hands-on learning. The dashboard and presentation are kept as submitted rather than being presented as a fully validated or production-ready business intelligence solution.

## Notes and limitations

- The uploaded materials do not include a separate dataset-source citation or download link. If the data came from a course or a third-party dataset, add the original attribution here before redistributing the data or publishing additional copies.
- The repository contains the PBIX report and its embedded Power BI model; it does not include separate raw CSV files.
- The business findings are descriptive. They show patterns in the available data and do not establish causal relationships.
- Metric definitions and filters should be checked in Power BI before reusing the displayed figures in another analysis.

## How to view

1. Install or open Microsoft Power BI Desktop.
2. Open `powerbi/Dashboard_PP_Brazilian.pbix`.
3. Use the available slicers and dynamic measure selector to explore the overview page.
4. Open the PDF in `report/` for the accompanying written interpretation and recommendations.
