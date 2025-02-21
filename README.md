# Sales & Customer Dashboards - Tableau Project

## Introduction

This project features two interactive Tableau dashboards designed to empower stakeholders, such as sales managers and executives, with actionable insights. These dashboards provide a comprehensive analysis of sales performance and customer behavior, enabling data-driven decision-making. The key objectives include tracking year-over-year sales trends, evaluating product subcategory performance, and understanding customer purchasing patterns.

## Data Source

The dataset consists of sales records with key attributes including:
- **Orders Table:** Contains order details, including order ID, order date, ship date, customer ID, and segment.
- **Customers Table:** Includes customer information, such as name, location, and customer ID.
- **Products Table:** Lists product details, including category, subcategory, and product ID.
- **Location Table:** Provides geographic data for regional sales analysis.

The dataset includes **9,994 rows** and is integrated into Tableau as a structured relationship between Orders, Customers, Location, and Products tables.

## Table Relationships

The dataset is structured with the following table relationships to enable seamless data analysis:
- **Orders Table** is linked to **Customers Table** via `Customer ID`.
- **Orders Table** is linked to **Products Table** via `Product ID`.
- **Orders Table** is linked to **Location Table** via `Region/State`.

#### **Screenshot:**
![image alt](https://github.com/soumil-saurya/Sales-Customer-Dashboards---Tableau-Project/blob/main/Table%20Relationship.png?raw=true)

## Dashboards Overview

### 1. Sales Dashboard

#### **Purpose:**

The Sales Dashboard provides an overview of sales metrics and trends to analyze year-over-year sales performance and understand key sales patterns.

#### **Key Features:**

- **KPI Overview:** Displays a summary of total sales, profits, and quantity for the current and previous year.
- **Sales Trends:** Monthly data visualization for sales KPIs, highlighting highest and lowest sales months.
- **Product Subcategory Comparison:** Year-over-year comparison of sales performance across product subcategories, including sales-to-profit comparisons.
- **Weekly Trends for Sales & Profit:** Weekly sales and profit trends for the current year, showing average weekly values and highlighting weeks above and below the average.

#### **Screenshot:**
![Sales Dashboard](/mnt/data/Screenshot%20(9).png)

### 2. Customer Dashboard

#### **Purpose:**

The Customer Dashboard provides an overview of customer data, trends, and behaviors. It helps marketing teams and management understand customer segments and improve customer satisfaction.

#### **Key Features:**

- **KPI Overview:** Displays total number of customers, total sales per customer, and total number of orders for the current and previous year.
- **Customer Trends:** Monthly data visualization for customer KPIs, highlighting highest and lowest sales months.
- **Customer Distribution by Number of Orders:** Analyzes customer purchasing behavior based on order frequency.
- **Top 10 Customers by Profit:** Ranks the top 10 customers generating the highest profits, including order count, current sales and profit, and last order date.

#### **Screenshot:**
![Customer Dashboard](/mnt/data/Screenshot%20(10).png)

## Design & Interactivity Features

- **Dashboard Dynamics:**  
  - Users can select any desired year to analyze historical data.  
  - Users can navigate between dashboards easily using interactive buttons or dropdown menus for a seamless experience.  
  - Interactive charts and graphs that allow data filtering directly through visual elements.

- **Data Filters:**  
  - Users can filter data by **product details** (category, subcategory) and **location details** (region, state, city).

## Project Highlights

- Advanced data visualizations for sales and customer analytics.
- Interactive filtering and drill-down capabilities for deeper insights.
- Year-over-year comparisons to track business growth and trends.

## Future Enhancements

- Adding customer segmentation analysis to identify high-value customers.
- Implementing predictive modeling for sales forecasting.
- Integrating with live data sources for real-time insights.

**Tools Used:** Tableau  
**Dataset:** Sales Dataset (Orders, Customers, Products, Location)









