# 📚 Library Management System using SQL

This project demonstrates the implementation of a **Library Management System** using **MySQL**. It includes creating and managing relational database tables, performing insightful data analysis using SQL queries, and uncovering business trends that can improve library services.

---

## 🎯 Objectives

- Design a structured relational database for managing books, members, and transactions.
- Analyze library data using **advanced SQL queries** to gain meaningful insights.
- Enable better decision-making by identifying trends such as high-demand books, overdue returns, and member activity.

---

## 🛠️ Technologies Used

- **Database:** MySQL
- **Tools:** MySQL Workbench
- **Language:** SQL (Structured Query Language)

---

## 🧱 Database Schema

The system includes the following core tables:

- `branches`: Library branches
- `employees`: Employees at each branch
- `members`: Registered library members
- `books`: Book information (ISBN, category, price, etc.)
- `issued_status`: Records of books issued to members
- `return_status`: Records of book returns
- `book_cnts`: Book-wise issue count

---
## 🧩 Schema
![Music Store Schema](Music_Store_Schema.png)

---

## 📊 Key SQL Queries for Insights

Here are some advanced queries included in the project:

1. **Top 10 Most Borrowed Books**
2. **Books with Zero Issues (Idle Stock)**
3. **Revenue by Book Category**
4. **Stock Availability Forecast**
5. **Overdue Books (30+ days)**
6. **First-Time vs. Returning Members**
7. **Most Active Days of the Week**
8. **Most Frequent Borrowers**
9. **Book Demand vs Availability**
10. **Branch-wise Issue Comparison**

👉 Full list of **20+ analytical queries** available in ``.

---
## 📌 Key Insights

- **Top Borrowed Books**: A small subset of books accounts for the majority of all issues, indicating strong preferences among readers.
  
- **High-Demand, Low-Stock Titles**: Several books are frequently requested while already issued, suggesting the need for additional copies.

- **Underutilized Inventory**: Roughly 30% of books have rarely or never been issued, consuming valuable shelf space without contributing value.

- **Overdue Trends**: Over 10% of books are overdue beyond 30 days, especially among newer members.

- **Returning Members Drive Usage**: Repeat users are responsible for over 75% of all issues.

- **Weekend Borrowing Peaks**: Most issues occur on Fridays and Saturdays, indicating high weekend activity.

- **Genre Revenue Trends**: Technology, Business, and Fiction genres generate the highest rental income.

---

## 📖 Data Story

The Library Management System database tells a powerful story about member behavior, stock utilization, and genre popularity:

- A core group of books dominates borrowing patterns, while many others are underused.
- Loyal, returning members are key to overall engagement and revenue.
- New members often borrow once and never return — a missed retention opportunity.
- Operational inefficiencies such as overdue returns and low-stock high-demand books cause circulation problems and member dissatisfaction.
- Strategic improvements in stock management and user engagement can significantly enhance library performance.

---

## 💡 Recommendations

- **📚 Purchase Additional Copies** of consistently high-demand books to reduce waitlists and improve satisfaction.

- **🗃️ Retire or Replace Idle Stock** that hasn’t been borrowed in months to make room for newer or trending books.

- **📩 Introduce Return Reminders & Penalties** to minimize overdue books and improve circulation efficiency.

- **🏆 Create Loyalty Programs** for returning members (e.g., early access, discounts) to encourage continued use.

- **📢 Promote Less Popular Genres** through newsletters, curated displays, or special reading programs.

- **🧑‍💼 Optimize Staff Scheduling** on peak days (e.g., Fridays and Saturdays) for better service.

- **🔁 Follow Up with First-Time Borrowers** via email or SMS to improve retention and re-engagement.

