# 📊 **E-Commerce Sales Dashboard – Power BI**

A fully interactive **E-commerce Sales Dashboard** built in **Power BI** using two datasets (**Details** and **Orders**) to analyze sales performance, customer behavior, product categories, payment modes, and profitability.

This project demonstrates skills in **data modeling, DAX, cleaning, visualization, and storytelling**.

---

## 🔍 **Project Overview**

This dashboard provides insights into:

* Total **Sales Amount**
* Total **Orders**
* Total **Profit**
* Average Order Value (**AOV**)
* Profit trends by month
* Sales by states, customers, payment mode, category, and sub-category

It helps understand which regions, categories, and products drive the most revenue, and which payment modes customers prefer.

---

## 🗂️ **Datasets Used**

The project uses two datasets:

### **1. Details Table**

Contains transactional-level information:

* Order ID
* Amount
* Profit
* Quantity
* Category
* Sub-Category
* Payment Mode

### **2. Orders Table**

Contains additional customer & order-related information:

* Order ID
* Customer Name
* City
* State
* Order Date

Both tables were connected using **Order ID** as the primary relationship.

---

## 🧮 **Calculated Column – AOV**

The **Average Order Value (AOV)** was not present in the dataset.
So, a new calculated column was created using DAX:

```
AOV = [Amount] / [Quantity]
```

This allows analysis of how much value each order contributes on average across categories and customers.

---

## 📈 **Key Insights From the Dashboard**

### ✔️ **Top KPIs**

* **438K** – Total Sales Amount
* **5615** – Total Orders
* **37K** – Total Profit
* **121K** – Average Order Value

### ✔️ **Visuals Included**

* **Bar charts** – Sales by State, Customers, Sub-Category
* **Donut charts** – Category-wise & Payment Mode distribution
* **Column chart** – Profit by Month
* **Dynamic Slicers** – Quarter, region options

