# 🛒 E-Commerce Customer Behavior Analysis & Dashboard

An end-to-end data analysis project exploring customer, order, payment, and product data from a real-world e-commerce dataset (Olist) — packaged with an interactive **Power BI** dashboard.

## 📌 Objective

Analyze e-commerce order and customer data to uncover patterns in purchasing behavior, payment preferences, delivery performance, and product trends, then present the findings through an interactive, filterable dashboard.

## 🛠️ Tech Stack

- **Power BI** — data modeling, DAX measures, and interactive dashboard
- **CSV / Olist Dataset** — customers, orders, order items, payments, products, sellers
- **Power Query** — data cleaning and transformation

## 📊 What This Project Covers

- Data cleaning and preprocessing across multiple linked datasets
- Relationship modeling between customers, orders, payments, and products
- Sales and revenue trend analysis over time
- Payment type and installment behavior analysis
- Product category performance
- Delivery time and order status analysis
- Customer segmentation and behavior patterns
- Interactive Power BI dashboard with slicers/filters for drill-down analysis

## 📸 Dashboard Preview

See the `Screenshot/` folder for dashboard views (`Dashboard_1.png` – `Dashboard_4.png`).

## 🔑 Key Insights

- *(Add 3–4 short bullet points here summarizing your top findings — e.g. best-selling categories, peak order periods, most-used payment method, average delivery time.)*

## 📁 Project Structure

```
E-commerce_project/
├── Code/
│   └── E-Commerce_Customer_Behavior.pbix       # Power BI dashboard file
├── Dataset/
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
├── Presentation/
│   └── E-Commerce_Customer_Behavior_PPT.pptx   # Project presentation
├── Report/
│   └── E-Commerce_Customer_Behavior.pdf        # Full project report
└── Screenshot/
    ├── Dashboard_1.png
    ├── Dashboard_2.png
    ├── Dashboard_3.png
    └── Dashboard_4.png
```

## ▶️ How to Run

1. Clone this repo:
   ```
   git clone https://github.com/VaibhavEng23/<your-repo-name>.git
   ```
2. Open `Code/E-Commerce_Customer_Behavior.pbix` in **Power BI Desktop**.
3. If prompted, update the data source paths to point to the CSV files in the `Dataset/` folder.
4. Explore the dashboard using the built-in filters and slicers.

## 📚 What I Learned

- Building relational data models across multiple linked tables in Power BI
- Writing DAX measures for business metrics (revenue, delivery time, order counts)
- Designing an interactive, filterable dashboard for non-technical stakeholders
- Translating raw transactional data into actionable business insights

---
*Part of my Data Analytics learning journey.*
