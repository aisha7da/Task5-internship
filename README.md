# Task5-internship

# 🎶 Chinook Database SQL Analysis

This repository contains my internship project analyzing the **Chinook music store database** using SQL and Python.  
The goal was to answer key business questions with SQL queries and visualize the results.

---

## 📌 Project Overview
The **Chinook Database** represents a digital media store with information about:
- Artists, Albums, Tracks
- Customers, Invoices, and Invoice Lines
- Employees, Genres, and Playlists

Using this data, I performed SQL queries to analyze **sales performance** and answer business-related questions.

---

## 🛠️ Tools & Technologies
- **SQLite3** (embedded database engine)
- **Pandas** (query execution & data manipulation)
- **Matplotlib** (data visualization)
- **Google Colab** (development environment)
- **Kaggle Dataset**: [Chinook Database](https://www.kaggle.com/datasets/ranasabrii/chinook/data)

---

## 📊 Key Tasks

### 1. Top-Selling Products
- Query to find top 10 products by units sold and by revenue.  
- **Visualization**: Horizontal bar chart of top tracks.

### 2. Revenue by Country
- Query to calculate total revenue per country.  
- **Visualization**: Bar chart comparing revenues across regions.

### 3. Monthly Performance
- Query to calculate revenue over time (monthly aggregation).  
- **Visualization**: Line chart of monthly revenue trends with month names (e.g., `2009-Feb`).

### 🔥 Bonus Tasks
- **Ranking with Window Functions**: Ranked products by revenue using `RANK()`.
- **Cumulative Revenue**: Running total revenue across months using `SUM() OVER`.
- **Top Customer per Country**: Found highest-spending customer in each country using `ROW_NUMBER()`.

