# Financial Revenue Analysis Dashboard (Power BI)

## Project Overview
This repository contains a comprehensive Financial Analysis Dashboard of ABC Company built using Power BI, designed to provide actionable insights into revenue performance, geographical sales, product success, and individual sales representative effectiveness. The dashboard leverages a detailed financial dataset to visualize key metrics and trends, enabling data-driven decision-making.

![Screenshot 2025-05-29 201428](https://github.com/user-attachments/assets/e10bc4e0-0199-44e8-a446-5ca49600f63f)


## **Dataset Used:**  <a href="DataSet.xlsx">DataSet.xlsx</a>
This dataset contains transactional financial data, including revenue figures, geographical information (countries, regions), product details, and sales representative data.

## Tools Used
* **Power BI Desktop:** For data transformation, measure creation, and dashboard design.

## Key Features & Measures
The dashboard includes several calculated measures to provide a robust financial overview:
* **Total Revenue:** `SUM(Sheet1[Revenue (USD)])` - Overall revenue generated.
* **Average Revenue:** `AVERAGE(Sheet1[Revenue (USD)])` - Average revenue per transaction.
* **Total Transaction:** `COUNT(Sheet1[First Name])` - Total number of transactions recorded.
* **Total Country:** `COUNT(Sheet1[Country])` - Total number of unique countries involved in transactions.

![image](https://github.com/user-attachments/assets/028c1b6e-0c7c-4ea8-b0bd-ea2819d385d8)

These measures are prominently displayed as **KPI Cards** on the dashboard for quick access to top-level metrics.


## Visualizations
The dashboard incorporates a variety of interactive visualizations to explore financial data from different perspectives:

* **Donut Chart: Total Revenue by Region**
    * Shows the proportional contribution of each geographical region to the total revenue.
* **Line and Clustered Bar Chart (Combined): Total Revenue & Average Revenue by Country/Region**
    * Provides a comparative view of total and average revenue across different countries and regions within a single interactive visual.
* **Treemap: Total Revenue by Store**
    * Visually highlights the revenue contribution of individual stores, making it easy to identify top-performing locations.
* **Area Chart: Total Revenue by Quarter**
    * Illustrates revenue trends and seasonality across different quarters.
* **Ribbon Chart: Total Revenue by Product and Store**
    * Displays revenue performance for products across various stores, revealing product-specific strengths in different locations.
* **Matrix: Sales Representative Performance**
    * A detailed table showing `Sales Representative`, `Total Revenue`, `Average Revenue`, and `Total Transaction` for individual sales team members.
 
![image](https://github.com/user-attachments/assets/121c589d-125b-41ba-a0e2-fe477a2dd619)


## Interactive Slicers
The dashboard is equipped with three interactive slicers to enable dynamic filtering and drill-down analysis:
* **Years Slicer:** Filter data by specific years.
* **Quarters Slicer:** Filter data by specific quarters.
* **Stores Slicer:** Filter data by individual stores.

![image](https://github.com/user-attachments/assets/250b13fc-da73-43ec-9ec5-68e2eef179d1)


## Key Insights from the Dashboard
Based on the data presented in the dashboard:

* **Overall Financial Performance:**
    * The business has generated a substantial **Total Revenue of $127.41 Million**.
    * The **Average Revenue per transaction is $39.04 Thousand**, indicating high-value sales.
    * There are **3 Thousand Total Transactions** and operations span across **3 Thousand Total Countries**.

* **Top Performers:**
    * **Store 1** is the leading revenue generator, contributing the largest share to the total revenue.
    * **SMARTPHONE** is the dominant product category in terms of total revenue across all products and stores.
    * Interestingly, **Store 2** stands out as having the highest sales specifically for **SMARTPHONES**, suggesting a strong specialization or focus in this product area.

* **Geographical Revenue Distribution:**
    * **Asia** is the primary revenue driver, accounting for a significant **61%** of the total revenue by region.
    * The **U.K.** follows as the second largest contributor with **32%** of the regional revenue.
    * The **USA** contributes **13%** of the regional revenue, making it another key market.


## **Dashboard.pbix:**  <a href="financial analysis dashboard.pbix">financial analysis dashboard.pbix</a>
## **Dashboard.pdf:**  <a href="financial analysis dashboard.pdf">financial analysis dashboard.pdf</a>
