# customer-behaviour-analysis-project
data analytics project showcaseing the customer behaviour using python, sql and powerbi.


# 📊 **Customer Shopping Behavior Analysis – End-to-End Data Analytics Project**

## 📘 **Overview**

This project provides a complete end-to-end analysis of customer shopping behavior using a dataset of 3,900 purchase records.
The goal is to help a retail company understand customer preferences, spending patterns, and loyalty behaviors so they can improve sales, marketing, and customer engagement strategies.

The analysis includes:

* Python-based data preparation
* SQL analysis on PostgreSQL
* An interactive Power BI dashboard
* A final report and presentation

---

## 📂 **Project Files**

* **📄 Business Problem Document** – Problem statement & requirements
  → *Business Problem Document.pdf* 
* **📊 Python Notebook (EDA + Cleaning)**
  → *Customer_Shopping_Behavior_Analysis.ipynb*
* **💾 SQL Queries**
  → *customer_behavior_sql_queries.sql* 
* **📈 Power BI Dashboard**
  → *customer_behaviour_dashboard.pbix*
* **📝 Final Analysis Report**
  → *Customer Shopping Behavior Analysis.pdf* 
* **🎤 Presentation**
  → *Customer-Shopping-Behavior-Analysis.pptx* 

---

## 🧵 **Dataset Summary**

* **Rows:** 3,900
* **Columns:** 18
* **Missing values:** 37 (only in Review Rating)
* **Key fields:**

  * *Age, Gender, Location, Subscription Status*
  * *Item Purchased, Category, Purchase Amount*
  * *Discount Applied, Previous Purchases, Review Rating*
  * *Season, Size, Color, Shipping Type*

---

## 🛠️ **Tools & Technologies Used**

### **Programming & Processing**

* Python (Pandas, NumPy, Matplotlib/Seaborn)
* Jupyter Notebook

### **Database & Querying**

* PostgreSQL
* SQL (Joins, Aggregations, Window Functions, CTEs)

### **Visualization**

* Power BI Desktop

### **Documentation**

* PDF Report
* PowerPoint (Gamma-based styling)

---

## 🔧 **Step-by-Step Workflow**

### **1️⃣ Data Preparation in Python**

Based on the notebook:

* Loaded dataset with `pandas`
* Checked structure using `df.info()` and summary using `df.describe()`
* Handled missing data → Imputed Review Rating using category-wise median
* Standardized column names (`snake_case`)
* Created new features:

  * `age_group` (using binning)
  * `purchase_frequency_days`
* Performed consistency checks (removed redundant `promo_code_used`)
* Loaded cleaned dataset into PostgreSQL for SQL analysis

---

### **2️⃣ SQL Analysis on PostgreSQL**

Using your SQL file, the following business questions were answered:

1. Revenue by gender
2. High-value discount users
3. Top 5 highest-rated products
4. Standard vs. Express shipping performance
5. Subscribers vs. non-subscribers spend comparison
6. Products most dependent on discounts
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Relationship between repeat buyers & subscription
10. Revenue contribution by age group

(Queries included CTEs, window functions, group by, and subqueries.)

---

### **3️⃣ Power BI Dashboard**

Dashboard includes:

* Sales KPIs
* Revenue by gender, age group, and subscription status
* Category-wise and product-level performance
* Discount & shipping behavior analysis
* Slicers for exploring demographics, categories, and seasons



---

### **4️⃣ Final Report & Presentation**

* **PDF report** covers full workflow, techniques, visuals, and insights
* **PPT presentation** summarizes key findings:

  * Women generate slightly higher revenue
  * Express shipping customers spend more
  * Subscribers spend more and have higher loyalty
  * Top-rated products should be promoted more
  * Loyalty programs can convert first-time buyers

---

## 📈 **Key Insights & Results**

* **Female customers** generate higher revenue
* **Express shipping** users spend **12% more**
* **Subscribers** contribute **higher revenue and retention**
* **Top-rated items** (Blouse, Dress, Shirt) show strong customer approval
* **Discount strategies** influence high-value shoppers
* **New customers = 50%** → Huge opportunity to convert to Returning & Loyal

---

## ▶️ **How to Run This Project**

### **1. Clone the Repository**

```bash
git clone https://github.com/yourusername/customer-shopping-behavior.git
cd customer-shopping-behavior
```

### **2. Install Python Libraries**

```bash
pip install -r requirements.txt
```

### **3. Run the Notebook**

Open

```
Customer_Shopping_Behavior_Analysis.ipynb
```

and run all cells.

### **4. Setup PostgreSQL**

* Create a database
* Import cleaned dataset
* Run all queries from:

  ```
  customer_behavior_sql_queries.sql
  ```

### **5. View Dashboard**

Open:

```
customer_behaviour_dashboard.pbix
```

### **6. Read Report & Presentation**

Available in `/reports` and `/presentation` directories.

---

## 🙋 **Contact**

If you want to connect or discuss this project:
**Name:** Tabish Sultan Mulla
**Email:** [mullatabish74@gmail.com](mailto:mullatabish74@gmail.com)
**Role:** Data Analyst



