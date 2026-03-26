# 📊 Electronics Retailer Case Study: KPI Analysis Challenge

## 🧾 Overview

You are a data analyst at a global electronics retailer with access to five key datasets:

* Sales
* Customers
* Products
* Stores
* Exchange Rates

The goal is to analyze these datasets and derive key business insights using KPI-driven analysis.

---

## 🎯 Scenario

The company leadership is looking to gain insights from **2024 sales data** to optimize operations under economic pressure.

Focus areas include:

* Product performance
* Customer demographics and geography
* Seasonal revenue trends
* Delivery performance
* Channel (Online vs In-Store) comparison

---

## 📌 Analysis Questions

### 1️⃣ Monthly Revenue Trend

Merge **Sales, Products, and Exchange Rates** to calculate total revenue (USD) by month for 2024.

---

### 2️⃣ Peak Month Analysis

From Q1 results:

* Identify **Top 3 revenue months**
* Calculate their **% contribution to total annual revenue**

---

### 3️⃣ Holiday Drivers

For the peak months identified in Q2:

* Find **Top 3 product categories**
* Based on **revenue contribution**

---

### 4️⃣ Delivery Performance

Calculate the **average delivery time** across all orders.

---

### 5️⃣ Country Delivery Issues

* Compute **average delivery time by store country**
* Identify **Top 5 slowest countries**

---

### 6️⃣ Channel Performance

Calculate **Average Order Value (AOV)**:

* Compare **Online vs In-Store**
* Across different **continents**

> Online = `store_key IS NULL` or `store_key = -1`

---

### 7️⃣ Volume Leaders

Identify **Top 5 product categories** by:

* Total **units sold**

---

### 8️⃣ Revenue Leaders

Identify **Top 5 product categories** by:

* Total **revenue (USD)**

---

### 9️⃣ Customer Profile

Analyze customer distribution and spending:

* By **Continent × Gender**
* Metrics:

  * Customer count
  * Total spending

---

### 🔟 Customer Loyalty

Calculate **repeat customer rate**:

* % of customers with **2 or more orders**
* Segmented by **continent**

---

## 🧠 Key Objectives

* Build a **data pipeline (Bronze → Silver → Gold)**
* Perform **KPI-driven analysis**
* Design a **star schema for analytics**
* Generate **business insights from structured data**

---

## 🚀 Outcome

This analysis helps the business:

* Understand revenue trends
* Identify top-performing products
* Improve delivery operations
* Compare sales channels
* Enhance customer targeting strategies

---
