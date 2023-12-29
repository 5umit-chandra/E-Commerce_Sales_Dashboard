# E-commerce Sales Dashboard Project
## Project Overview
This Power BI dashboard, named **[E-Commerce_Sales_Dashboard.pbix](E-Commerce_Sales_Dashboard.pbix)**  is using hypothetical data to simulate a real-world scenario. 
The project revolves around two key datasets, "Orders.csv" and "Details.csv," interconnected through the common field Order ID.

## Key Visualizations

1. **Quarterly Insights Slicer:** This slicer empowers users to dynamically filter data by quarters, offering a snapshot of sales trends over time.

2. **Regional Focus Slicer:** The state filter slicer enables users to explore and analyze sales data on a state level, providing a granular view of regional performance.

3. **Monthly Profit Trends _(Stacked Column Chart)_:** Visualize the distribution of profit across months to identify potential seasonal patterns or trends.

4. **Profit Breakdown by Sub-Category _(Stacked Bar Chart)_:** Uncover the contribution of each sub-category to overall profit, facilitating product-level performance evaluation.

5. **Key Performance Cards:**
    - **Amount, Quantity, and Profit:** Quick reference cards summarizing essential metrics.
    - **Average Order Value _(AOV)_:** Computed as [Amount]/[Quantity], offering insights into transaction efficiency.
    - **Sales Distribution by State _(Stacked Bar Chart)_:** Explore the distribution of sales amounts across different states, providing insights into regional performance.

6. **Payment Mode Preferences _(Donut Chart)_:** Understand customer payment preferences by visualizing the quantity sold for each payment mode.

7. **Top Customers by Amount _(Stacked Column Chart)_:** Identify top-performing customers based on the sum of amounts spent, aiding in customer-centric strategies.

8. **Product Category Popularity _(Donut Chart)_:** Gain insights into product category performance by visualizing the quantity sold in each category.


## Technical Details
**Data Sources:** Simulated data sourced from the internet, comprising [Orders.csv](Orders.csv) and [Details.csv](Details.csv)

**Data Connection:** Established through the common field `Order ID`

**DAX Measures:** AOV (Average Order Value) is Computed as `[Amount]/[Quantity]`

**How to Use**
- Download and open **[E-Commerce_Sales_Dashboard.pbix](E-Commerce_Sales_Dashboard.pbix)** in Power BI Desktop.
- Use slicers to filter data based on quarters and states.

## Key Learning Objectives
- **Temporal Analysis:** Understand how sales fluctuate across different time periods.
- **Regional Insights**: Explore and analyze sales trends at the state level.
- **Product and Customer Focus:** Evaluate product and customer performance to inform business strategies.

## Conclusion
This project serves as a learning tool, demonstrating the application of Power BI in analyzing and visualizing hypothetical e-commerce sales data. Feel free to explore, customize, and adapt the dashboard to further your understanding of data analytics and visualization techniques.

> [!NOTE]
>The data used in this project is entirely simulated and created for educational purposes. This project is not intended to represent or reflect any real business, and the > results and insights derived are based on fictional data.