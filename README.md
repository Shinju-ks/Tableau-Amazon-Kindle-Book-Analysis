# Tableau Amazon Kindle Book Analysis

## 📌 Project Overview
This project presents an **in-depth analysis of Amazon Kindle book sales data** using **Tableau**.
The dataset, sourced from **Kaggle**, contains details of **130 Kindle books**, including product attributes, reviews, pricing, and sales information.

The objective is to uncover insights into **book performance, pricing trends, and sales dynamics** through three interactive dashboards:
1. **Book Overview**
2. **Price Analysis**
3. **Sales Dynamics**

---

## 📂 Dataset
- **Source**: Kaggle
- **Records**: 130 Kindle books
- **Fields Included**:
- **ASIN** (Product ID)
- Title
- Author
- Sold By
- Image URL
- Product URL
- Stars (Ratings)
- Reviews
- Price
- Is Kindle Unlimited (Yes/No)
- Category ID (Bestseller, Editor’s Pick, Goodreads Choice)
- Publish Date
- Category Name

---

## 📊 Dashboards Created

### 1. 📚 Book Overview Dashboard
- **Homepage Navigation** to switch across dashboards
- **Card Visuals**:
- Total Books
- Total Genres
- Total Authors
- **Top 5 Authors** with the most reviews
- **Top 10 Most Reviewed Books** (using Top N filters and parameters)
- **Top 7 Bestselling Books**
- **Category Breakdown**:
- Kindle Unlimited
- Bestseller
- Editor’s Pick

---

### 2. 💲 Price Analysis Dashboard
- **Card Visuals**:
- Average Price
- Maximum Price
- **Book Count by Price Category**: Grouped into custom categories (0–10, 10–20, … >50)
- **Price-Based Sales Analysis**
- **Book Count by Year and Month** (Filtered to include publish date from 2000 onwards)
- **Average Price by Publish Date**
- **Average Price by Publisher**

---

### 3. 📈 Sales Dynamics Dashboard
- **Card Visuals**:
- Total Sales
- Top-Selling Genres
- **Top 5 and Bottom 5 Genres** by Sales (with conditional formatting)
- **Bestseller in Each Genre**
- **Genre Sales Analysis**
- **Sales vs. Star Ratings** (Grouped)
- **Top Authors by Genre** (using contains parameter for filtering)

---

## 🛠️ Tableau Features & Techniques Used
- **Parameters**: For Top N analysis (Top authors, Top reviewed books)
- **Contains Parameter**: For flexible author/genre filtering
- **Filters**: Applied across dashboards for interactivity and focused insights
- **Top N Filters**: Used for Top 5 / Top 10 / Top 7 analysis
- **Grouping**:
- Price categories (7 ranges)
- Sales vs. Ratings grouping
- **Card Visuals**: Used for KPI-style summary metrics
- **Tree Map, Line Chart, Pie Chart, Tables**: To represent data in multiple dimensions
- **Conditional Formatting**: Highlighting top and bottom performing genres
- **Navigation Buttons**: For smooth switching between dashboards

---

## 🔑 Key Insights
- Top authors and genres consistently dominate both **reviews and sales**.
- **Price below $20** books generated the **highest sales volume**.
- Certain genres outperform others significantly in **reviews and revenue**.
- **Higher ratings correlate positively with stronger sales performance**.
- Category labels such as **Kindle Unlimited, Bestseller, and Editor’s Pick** play a key role in visibility and popularity.

---

## 📷 Dashboard Previews

### 1. Book Overview
![Book Overview](Book%20Analysis.png)

### 2. Price Analysis
![Price Analysis](Price%20Analysis.png)

### 3. Sales Dynamics
![Sales Dynamics](Sales%20Dynamics.png)
---

## 🚀 How to Use
1. Download the Tableau Workbook (`.twb` or `.twbx`).
2. Open it in **Tableau Desktop** or **Tableau Public**.
3. Use the homepage to navigate between dashboards.
4. Apply filters and parameters to explore insights dynamically.

---

## 📌 Conclusion
This Tableau project highlights how **reviews, pricing strategies, and genres** impact the success of Amazon Kindle books.
It demonstrates the power of Tableau in **data storytelling, interactive dashboards, and business insight generation**.

---

## 📝 Author
- **Shinju**
- Aspiring **Data Analyst / Business Analyst**
- Skills: Tableau, Power BI, SQL, Data Visualization, Business Analytics
