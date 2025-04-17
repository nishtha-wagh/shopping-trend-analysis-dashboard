
# 🛍️ Customer Shopping Trends Dashboard

Welcome to our project for IFT 533: Data Visualization & Reporting for IT. This project involves the implementation of interactive Tableau dashboards based on a simulated dataset of consumer shopping trends. The dashboards aim to uncover insights into customer demographics, purchasing behavior, seasonal trends, and more.

## 📊 Project Overview

This project includes **three interactive Tableau dashboards**, each targeting a different aspect of customer behavior and business operations:

### 1. **Customer Insights and Seasonal Trends**
- **Customer Age & Gender Distribution**
- **Seasonal Product Category Trends by State**

🔍 _Used by marketing and sales teams for campaign planning and inventory optimization._

### 2. **Revenue Drivers and Payment Insights**
- **Top/Bottom Spending States**
- **Revenue by Categories and Items**
- **Consumer Payment Methods**
- **Subscribers vs Non-Subscribers**

💰 _Helps sales, marketing, and finance teams to track revenue streams and payment behavior._

### 3. **Customer Loyalty and Shipping Preferences**
- **Discount Applications**
- **Loyal Customer States**
- **Seasonal Shipping Preferences**
- **Shipping Methods by Product Category**

🚚 _Aids supply chain and customer experience teams in shipping strategy and loyalty program development._

## 📂 Dataset Summary

The dataset is a simulated retail dataset including:
- Customer demographics (age, gender, income)
- Product details (category, size, color)
- Purchase details (amount, payment, shipping, discounts)
- Geographic and seasonal context

**Total Attributes:**
- `Customer ID`, `Age`, `Gender`, `Item Purchased`, `Category`, `Purchase Amount`, `Location`, `Size`, `Color`, `Season`, `Review Rating`, `Subscription Status`, `Payment Method`, `Shipping Type`, `Discount Applied`, `Promo Code Used`, `Previous Purchases`, `Frequency of Purchases`

## 🧹 Data Preprocessing in Tableau

- **Age Categorization:** Young Adult (18–24), Adult (25–39), Middle-Aged (40–59), Senior (60+)
- **State Ranking:** Based on total purchases using `RANK(SUM([Previous Purchases]))`
- **Color-coded State Maps:** Highlight "Top N" states for loyalty or spending
- **Top Category by State and Season:** Using FIXED LOD expressions

## 📈 Visualizations

Includes 13 core plots:
1. Age Category Distribution (Bubble Chart)
2. Gender Distribution (Stacked Bar)
3. Top Product Categories by Season and State (Map)
4. Top Spending States (Bar)
5. Bottom Spending States (Bar)
6. Top Revenue Categories (Bar)
7. Top Revenue Items (Bar)
8. Payment Method Breakdown (Bar)
9. Subscribers vs Non-Subscribers (Donut)
10. Discount Usage Overview (Bar)
11. Customer Loyalty by State (Map)
12. Shipping Preferences by Season (Bar)
13. Shipping Preferences by Category (Bar)

## 🧩 Interactivity Features

- **Sliders** for dynamic filtering (e.g., Top N States, Loyal States)
- **Dropdowns** for seasonal filtering
- **Action Filters** to link charts across dashboards
- **Drilldowns** on product categories and customer segments

## 👥 Stakeholders

This dashboard is designed for:
- **Marketing Teams**
- **Finance Departments**
- **Product Developers**
- **Customer Experience Analysts**
- **Supply Chain Managers**
- **Executive Leadership**

Each team benefits from tailored insights supporting better data-driven decisions.

## 🌐 Tableau Public Link

Explore the live dashboard on Tableau Public:

👉 [Click here to view the dashboard](https://public.tableau.com/shared/WB2TNHGZP?:display_count=n&:origin=viz_share_link)
