
# 💸 Personal Expense Tracker Dashboard (Excel + Pivot Tables)

This project is a **personal finance tracker dashboard** designed in Excel. It helps users monitor income, spending habits, top expenses, and weekly/monthly trends through a visually engaging and interactive interface.

---

## 🧠 Project Overview

The goal of this project was to create a **comprehensive personal expense dashboard** using Excel to improve financial literacy, identify spending patterns, and encourage smarter budgeting decisions. The raw dataset was unstructured and required significant cleaning and transformation before meaningful analysis could be performed.

---

## 🔧 What I Did

### 1. **Data Cleaning & Preprocessing**
- Cleaned messy and inconsistent **date formats** and converted them into standard Excel date objects.
- Cleaned **currency columns** to remove symbols, formatting inconsistencies, and convert them into numeric values for calculations.
- Standardized inconsistent text entries in the **description column**.

### 2. **Feature Engineering**
- Extracted **three new columns** from the `Description` field:
  - `Category` (e.g. Food, Transport, Self Development)
  - `Subcategory` (e.g. POS Payment, SMS Alert Fee)
  - `Category Type` (e.g. Debit or Credit)
- Created **Month** and **Weekday** columns from the `Transaction Date` column to enable trend analysis.

### 3. **Pivot Tables & Analysis**
- Built pivot tables to summarize:
  - Monthly income and expenses
  - Weekly spending habits
  - Top spending categories
  - Income sources
- Identified maximum income and spending periods for easy reference.

### 4. **Dashboard Creation**
- Designed a user-friendly, **interactive Excel dashboard** with:
  - Monthly and weekly trends (bar charts)
  - Donut chart showing income source proportions
  - Top 6 spending categories with icons and values
  - Summary KPIs including total income, total spending, and max income/spending
  - Personalized theme (colors, fonts, icons) for better visual storytelling

---

## 📊 Tools Used

- **Microsoft Excel**
- Pivot Tables
- Formulas (e.g. `TEXT`, `IF`, `VLOOKUP`, `SUMIFS`, `MONTH`, `WEEKDAY`)
- Charts (Bar, Donut, Line)
- Conditional Formatting

---

## 🌟 Features

- Clean and interactive dashboard for non-technical users
- Quick insights into income vs. expenses
- Visual breakdown of where money goes
- Designed for both personal use and beginner-level financial literacy training

---

## 📌 Screenshots

![Dashboard Overview](./Screenshot%202025-05-12%20163758.png)  
![Top Spending & Weekly Trends](./Screenshot%202025-05-12%20164217.png)

---

## 🚀 Future Improvements

- Automate data cleaning using Python or Power Query
- Add filters for time ranges or transaction types
- Make the tracker dynamic with slicers and VBA (for advanced Excel users)

---

## 👩‍💻 About Me

I'm Precious O. Ochiobi — a data analyst passionate about building data-powered tools that solve real-world problems. I designed this tracker to make personal finance more intuitive and actionable for everyday users.

---

## 📬 Let's Connect

If you’d like to collaborate or give feedback, feel free to reach out on [LinkedIn] or fork the repo!
