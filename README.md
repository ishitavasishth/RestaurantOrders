# 🍽️ Restaurant Menu & Order Insights using SQL

Welcome to a SQL-driven analysis project uncovering patterns in customer ordering behavior and menu performance. The goal? Deliver insights that drive smarter **menu optimization**, **inventory planning**, and **promotions strategy**.

---

## Business Objectives

This project addresses three key objectives across the restaurant's data ecosystem:

### Objective 1: Understand the Menu

**Data Source:** `menu_items`  
**Key Insights:**
- Total number of items on the menu  
- Most and least expensive dishes overall  
- Most and least expensive Italian dishes  
- Category-wise distribution and average pricing  

**Business Impact:**
- Helps in **pricing decisions** and identifying **premium vs. low-margin items**  
- Useful for **menu engineering** — which items to promote, replace, or reprice  
- Category popularity guides **inventory planning**

---

### 🧾 Objective 2: Explore Order Trends

**Data Source:** `order_details`  
**Key Insights:**
- Order date range and volume  
- Total items ordered and peak order sizes  
- Orders with unusually high item counts  

**Business Impact:**
- Enables **staffing optimization** during high-demand periods  
- Identifies **bulk buyers** or large-party behavior  
- Helps forecast **inventory restocking** windows

---

### 👥 Objective 3: Analyze Customer Behavior

**Data Source:** `menu_items` + `order_details` (joined)  
**Key Insights:**
- Most and least frequently ordered dishes  
- Category affiliation of top/low performers  
- Top 5 highest-spending orders and their composition  

**Business Impact:**
- Pinpoints **best-selling items** for bundling or loyalty offers  
- Identifies **underperforming dishes** to phase out or reposition  
- Assists in **personalization efforts** by understanding spending patterns

---

## 📌 Tools Used

- **SQL** (MySQL syntax)  
- Data sourced from two tables:
  - `menu_items`: Dish names, categories, and pricing  
  - `order_details`: Order-level and item-level transaction history

---

## Sample Business Questions Answered

- What’s the average dish price in each category?  
- How many orders had more than 12 items?  
- Which items were ordered the most—and the least?  
- Which single order had the highest total spend?  
- What’s the breakdown of dishes in top spending orders?

---



## 👩‍💻 Author

**Ishita Vasishth**  
*Data-Driven Storyteller | Marketing Analytics @ UT Austin*  
[Portfolio](https://iv3848.carrd.co) • [LinkedIn](https://www.linkedin.com/in/ishitavasishth) • [GitHub](https://github.com/ishitavasishth)
