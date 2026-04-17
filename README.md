🍕 Pizza Sales SQL Project
🔎 Overview
This repository contains a SQL‑based analytics project built on the Pizza Day dataset, designed to answer key business questions about sales, revenue, and customer behavior. By leveraging SQL queries, the project demonstrates how raw transactional data can be transformed into actionable insights for decision‑making.

The project highlights data modeling, query optimization, and business intelligence techniques—making it a valuable resource for both learning SQL and applying it to real‑world retail scenarios.

├── /SQL_Scripts
│   ├── total_orders.sql
│   ├── total_revenue.sql
│   ├── highest_priced_pizza.sql
│   ├── most_common_size.sql
│   ├── top5_pizza_types.sql
│   ├── category_quantity.sql
│   ├── hourly_distribution.sql
│   ├── avg_orders_per_day.sql
│   ├── cumulative_revenue.sql
│   └── README.md
├── /DataModel
│   └── pizza_day_schema.png
└── Pizza_Sales_SQL_Project.pdf
📈 Business Problems & Solutions
1. Total Orders Placed
Query: Counts all order IDs.

Insight: Total orders = 21,350.

Value: Establishes baseline demand.

2. Total Revenue Generated
Query: Multiplies quantity × price across all orders.

Insight: Total revenue = $817,860.05.

Value: Provides a clear measure of business performance.

3. Highest‑Priced Pizza
Query: Joins pizza types with prices, sorted descending.

Insight: The Greek Pizza at $35.95.

Value: Identifies premium product positioning.

4. Most Common Pizza Size Ordered
Query: Groups by pizza size, counts orders.

Insight: Large size dominates with 18,526 orders.

Value: Guides inventory and packaging decisions.

5. Top 5 Most Ordered Pizza Types
Query: Aggregates quantities by pizza type.

Insight:

Classic Deluxe – 2,453

Barbecue Chicken – 2,432

Hawaiian – 2,422

Pepperoni – 2,418

Thai Chicken – 2,371

Value: Highlights customer favorites for promotions.

6. Category‑Wise Quantity Ordered
Query: Joins pizzas with categories, sums quantities.

Insight:

Classic – 14,888

Supreme – 11,987

Veggie – 11,649

Chicken – 11,050

Value: Reveals demand distribution across categories.

7. Hourly Distribution of Orders
Query: Groups orders by hour of day.

Insight: Peak hours: 12 PM – 6 PM, with highest at 12 PM (2,520 orders).

Value: Supports staffing and delivery scheduling.

8. Average Orders Per Day
Query: Groups by date, calculates average.

Insight: Consistent daily demand patterns.

Value: Helps forecast daily operational needs.

9. Cumulative Revenue Over Time
Query: Window function to calculate cumulative revenue.

Insight: Revenue steadily increases, e.g., $19,399.05 by Jan 8, 2015.

Value: Tracks growth trajectory and long‑term performance.
