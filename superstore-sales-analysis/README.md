# 🛒 Superstore Sales Analysis – Yash Jha

This project analyzes the **SuperStore Orders Dataset** to uncover insights related to sales performance, profitability, customer segments, product categories, and shipping efficiency using **Python**, **Pandas**, and **Jupyter Notebook**.

---

## 📌 Project Objectives
- Clean and preprocess the dataset for analysis  
- Convert date columns and compute new KPIs  
- Perform exploratory data analysis (EDA)  
- Analyze sales and profit across regions, categories, and segments  
- Identify profitable and loss-making product sub-categories  
- Understand shipping efficiency and discount patterns  
- Produce business insights useful for decision-making  

---

## 📊 Key Insights

### **1. Business Performance Overview**
- **Total Sales:** ₹12,642,905  
- **Total Profit:** ₹1,469,034  
- **Average Discount:** 14.3%  
- **Average Shipping Time:** 3.57 days  

---

### **2. Regional Analysis**
- **Central region** dominates both sales and profit → strongest market  
- **South, North, North Asia** show strong profitability  
- Weak markets include **Canada, Caribbean, Southeast Asia** with very low profit contribution  

---

### **3. Category Profitability**
| Category          | Total Profit |
|------------------|--------------|
| Technology        | ₹663,779     |
| Office Supplies   | ₹518,474     |
| Furniture         | ₹286,782     |

**Technology** is the most profitable category.  
**Furniture** lags due to higher discounts and shipping costs.

---

### **4. Sub-Category Profitability**
Top Performers:
- **Copiers:** ₹258,568  
- **Phones:** ₹216,717  

Loss Maker:
- **Tables:** –₹64,083  
  - Likely due to heavy discounts, high shipping costs, and return issues.

---

### **5. Shipping Performance**
- Average shipping time is **3.57 days**  
- Useful for logistics optimization and service-level improvement  

---

## 🧹 Data Cleaning Steps
- Converted `order_date` and `ship_date` to datetime  
- Converted `sales` to numeric  
- Created new metric:  
  - **shipping_days = ship_date – order_date**  
- Removed or handled inconsistent values  

---

## 🛠 Tools & Technologies
- **Python 3**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
- Matplotlib / Seaborn for visuals

---




