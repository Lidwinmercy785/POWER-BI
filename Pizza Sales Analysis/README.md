🍕 Spice & Slice – Pizza Sales Analysis Dashboard
Project Overview

This project presents a comprehensive Power BI dashboard designed to analyze one year of sales data for Spice & Slice, a pizza restaurant.
The dashboard highlights sales trends, category performance, best & worst performing pizzas, and key business metrics, helping stakeholders make data-driven decisions to improve menu offerings and operational strategy.

📌 Table of Contents

- Introduction

- Dataset

- Key Features

- Steps Involved

- Dashboard

- Navigation

- Technologies Used

- Conclusion

📖 Introduction

The Pizza Sales Analysis Dashboard provides an end-to-end analysis of sales performance between Jan 15 – Dec 15, 2015.
It allows users to explore revenue, orders, pizza categories, sizes, and product performance. The dashboard is designed for restaurant managers, business analysts, or anyone wanting to understand customer ordering trends and menu performance.

📁 Dataset

The dataset used in this project includes:

Pizza orders dataset (CSV/Excel format)

Fields such as:

- Order ID

- Pizza Name

- Category (Classic, Veggie, Supreme, Chicken)

- Size (S, M, L, XL, XXL)

- Quantity

- Price

- Order Date & Time

This dataset was cleaned and transformed before visualization.

⭐ Key Features
Interactive Visualizations

- Analyze total revenue, orders, and pizzas sold.

- Track ordering patterns across months, days, and categories.

- Size & Category Slicers

- Filter all visuals based on pizza category and size.

- Best/Worst Performance Insights

- Identify top and bottom 5 pizzas based on revenue, orders, and quantity.

- KPI Cards

- Total Revenue

- Total Orders

- Total Pizzas Sold

- Average Pizzas Per Order

- Average Order Value

- Navigation Buttons

Seamless movement between dashboard pages (Home → Sales Overview → Best/Worst Pizzas).

🧩 Steps Involved
1. Data Import and Transformation

- Import the pizza sales dataset.

-Handle missing values in category and size columns.

- Convert date & time to proper datetime format.

- Extract weekday and month for trend analysis.

2. Data Cleanup

- Remove unnecessary fields.

- Create structured columns:

- Month

- Weekday

- Hour

- Pizza Size Category

- Apply all transformations using Power Query.

3. Creating Slicers and Visuals

- Add slicers for Category and Size.

Create:

- Line chart → Orders by Month

- Bar chart → Revenue by Category

- Bar chart → Orders by Day

- Donut chart → Revenue by Size

- Multiple KPI cards

4. DAX Measures

- Created core DAX measures including:

- Total Revenue

- Total Orders

- Total Pizzas Sold

- Average Order Value

- Revenue by Category

- Orders by Month/Day

- Filtering measures to perform top/bottom analysis

5. Best/Worst Selling Pizza Analysis

Top 5 pizzas by:

- Revenue

- Orders

- Quantity

Bottom 5 pizzas by:

- Revenue

- Orders

- Quantity

These visuals help managers identify which pizzas need improvement or promotional support.

6. Visual Representation

The dashboard includes:

- Clustered bar charts

- Line charts

- Area charts

- KPI cards

- Category slicers

- Buttons for navigation

All visuals follow consistent styling, color theme, and layout.

7. Tooltip & Drillthrough Pages

A dedicated tooltip page provides pizza-level information.

-Users can hover or drill down to view:

-Category

- Size

- Revenue

- Quantity sold

8. Review & Validation

- All measures validated to ensure accurate totals.

- Missing values replaced properly.

- Slicers synchronized across pages for a smooth user experience.

🧭 Dashboard Navigation

The dashboard contains three main pages:

1. Home Page

Entry page with navigation buttons.

Provides quick links to the main analytics sections.

2. Sales Overview

Executive summary of key business KPIs.

Shows sales performance across months, days, categories, and sizes.

3. Best & Worst Selling Pizzas

Displays top & bottom performers based on revenue, orders, and quantity.

You can switch between pages using the navigation buttons.

🛠 Technologies Used

Power BI – Interactive dashboard creation

Power Query – Data transformation & cleaning

DAX – Measures and business calculations

Excel/CSV – Dataset source

📊 Dashboard Screenshots

<img width="1097" height="705" alt="FRONT PAGE" src="https://github.com/user-attachments/assets/3ae31bc5-9ddb-4eb7-b178-22b4270cc01a" />
<img width="1230" height="732" alt="PAGE 1" src="https://github.com/user-attachments/assets/140997de-4748-4319-a427-eec2ae2c8b3a" />
<img width="1230" height="732" alt="PAGE 1" src="https://github.com/user-attachments/assets/b027e9cc-dd54-466f-9eea-4a2e94eb8aa6" />




🎯 Conclusion

The Spice & Slice Pizza Sales Analysis Dashboard delivers meaningful insights into restaurant performance.
It uncovers patterns in customer orders, highlights profitable categories, and identifies weak-performing items.
This dashboard empowers businesses to:

- Improve menu strategy

- Plan inventory efficiently

- Understand customer preferences

- Boost sales through data-driven decisions
