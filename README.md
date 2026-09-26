# Pizza Sales Report - Power BI Dashboard

This repository contains the source documentation and overview for the Pizza Sales Report Power BI solution. The dashboard provides comprehensive business intelligence into sales performance, customer ordering trends, and product-level profitability.

## 📊 Dashboard Structure

The solution consists of two core views:

### 1. Overview Dashboard

<img width="1186" height="667" alt="image" src="https://github.com/user-attachments/assets/a613a717-ffe9-46e2-8c3e-0bc826978637" />

* **KPI Summary Cards:** Displays high-level metrics including Total Revenue ($817,860$), Total Orders ($21,350$), Total Pizzas Sold ($49,574$), Average Pizza per Order ($2.32$), and Average Revenue per Order ($38$).
* **Trend Analysis:** Visualizes daily order distribution across the week (peaking on Friday) and monthly revenue/order trajectories (peaking in July).
* **Category & Size Breakdown:** Evaluates sales distribution across pizza categories (Classic, Supreme, Chicken, Veggie) and physical sizes.


### 2. Best / Worst Sellers Dashboard

<img width="1199" height="669" alt="image" src="https://github.com/user-attachments/assets/3066c4bc-5ab6-436c-a53c-044b215c5621" />

* **Revenue Leaders & Laggards:** Highlights the top 5 and bottom 5 performing pizzas by total revenue (e.g., Thai Chicken Pizza leading revenue vs. Brie Carre Pizza at the bottom).
* **Quantity & Order Rankings:** Analyzes products by total volume sold and total order frequency to optimize inventory and menu curation.


## 🛠️ Features & Filters
* **Dynamic Slicers:** Filter data seamlessly by Month, Pizza Category, and specific Pizza Name.
* **Conditional Formatting & Insights:** Integrated text summaries highlighting peak sales drivers (e.g., Classic category and large sizes generating maximum sales).


## 🚀 Getting Started
1. Open the `.pbix` file in Microsoft Power BI Desktop.
2. Connect your underlying SQL or CSV data source containing the pizza sales transactions.
3. Refresh the dataset to populate the visuals.
