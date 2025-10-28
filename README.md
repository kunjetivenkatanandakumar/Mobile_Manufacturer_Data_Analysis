# 📱 Mobile Manufacturer Data Analysis (Advanced SQL Project)

## 📘 Project Overview
This project focuses on **advanced SQL data analysis** for a mobile phone manufacturing company.  
The database — **Cellphones Information** — contains details of mobile phone sales and customer transactions.  
The objective is to write optimized SQL queries that answer complex business questions involving sales, customers, and manufacturer performance.

---

## 🧩 Business Scenario
The **Cellphones Information** database stores details across multiple dimensions:

| Table | Description |
|--------|-------------|
| `Dim_Manufacturer` | Information about phone manufacturers |
| `Dim_Model` | Model-specific details (model name, price, release year, etc.) |
| `Dim_Customer` | Customer demographic data |
| `Dim_Location` | Geographic data such as state, ZIP, and country |
| `Fact_Transactions` | Sales transaction data (quantities, prices, and dates) |

The goal is to analyze this data to answer **real-world business questions** about performance, trends, and profitability.

---

## 🧮 SQL Case Study Rules
- All SQL queries should be written **between BEGIN and END markers** in the answer template.  
- **Do not modify** the template structure or database schema.  
- Only **one query per question** should return a single result table.  
- **Plagiarism is strictly prohibited.**  
- The final submission should be a **zipped SQL file**, renamed as:  
  `youremail@example.com-Advance.sql`

---

## 💡 Business Questions Answered

### **Data Exploration**
1. List all states where customers have purchased cellphones from **2005 to today**.  
2. Find the **state in the US** buying the most **Samsung** phones.  
3. Show the **number of transactions** for each model per ZIP code per state.  
4. Identify the **cheapest cellphone** (include price).  

### **Aggregations & Averages**
5. Find the **average price per model** among the **top 5 manufacturers** by total sales quantity.  
6. List customers and their **average amount spent in 2009**, where it exceeds **$500**.  

### **Trend & Ranking Analysis**
7. Find models that were in the **Top 5 in sales quantity** in **2008, 2009, and 2010** simultaneously.  
8. Show the **manufacturer with the 2nd highest sales** in **2009** and **2010**.  
9. Identify manufacturers that **sold in 2010 but not in 2009**.  
10. Find the **Top 100 customers**, their **average spend and quantity per year**, and the **percentage change in spend** year-over-year.

---

## 🧠 Key Insights
- Determined sales dominance by manufacturer and model across years.  
- Identified customer loyalty and spending growth.  
- Highlighted high-value regions and underperforming locations.  
- Supported strategic decisions for inventory and marketing optimization.  
