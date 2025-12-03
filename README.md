

# 📊 **Superstore Sales Dashboard – Power BI**

This project presents an interactive **Sales & Profit Analytics Dashboard** built using the **Sample Superstore Dataset** in **Power BI**.
The goal of the dashboard is to analyze sales performance, profitability, customer segments, and regional performance through clean and interactive visuals.

---

## 🎯 **Project Objectives**

* Understand key business metrics using KPIs
* Identify top-performing categories & sub-categories
* Analyze monthly sales trends
* Evaluate customer segments
* Explore geographic sales distribution
* Build a clean, professional Power BI dashboard

---

## 📁 **Dataset Used**

**Sample Superstore Dataset**
Contains fields such as:

* Order Date, Ship Date
* Category, Sub-Category
* Segment, Region, State
* Sales, Quantity, Profit, Discount
* Customer Details

---

## 🛠️ **Tools & Technologies**

* **Power BI Desktop**
* Power Query for data cleaning
* DAX for calculated measures
* Data modeling (relationships, hierarchies)

---

## 🧹 **Data Cleaning & Preparation**

Performed inside **Power Query**:

* Removed blank rows & duplicate rows
* Fixed date format issues using locale settings
* Converted Order Date & Ship Date to proper Date types
* Created new fields:

  * **Month Name**
  * **Year**
* Removed errors from the dataset
* Ensured correct data types for all fields

---

## 🧮 **DAX Measures Created**

```DAX
Total Sales = SUM('Sample - Superstore'[Sales])

Total Profit = SUM('Sample - Superstore'[Profit])

Total Orders = COUNT('Sample - Superstore'[Order ID])

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

AOV = DIVIDE([Total Sales], [Total Orders])
```

---

## 📊 **Dashboard Features**

### 🔹 **1. KPI Cards**

* **Total Sales**
* **Total Profit**
* **Profit Margin %**
* **Total Orders**
* **Average Order Value (AOV)**

These provide a quick overview of business performance.

---

### 🔹 **2. Sales by Category (Bar Chart)**

Shows how Technology, Furniture, and Office Supplies contribute to total sales.

---

### 🔹 **3. Total Profit by Sub-Category (Bar Chart)**

Helps identify the most profitable and least profitable product groups.

---

### 🔹 **4. Total Sales by Month (Line Chart)**

Visualizes sales trends across months.

---

### 🔹 **5. Sales by State (Map Visual)**

Geographical distribution of sales across United States.

---

### 🔹 **6. Filters (Slicers)**

Interactive slicers for:

* **Category**
* **Segment**

These enhance the dashboard’s interactivity.

---

## 🎨 **Design Enhancements**

* Light grey borders around KPI cards
* Clean, minimalist layout
* Dashboard title centered at the top
* Consistent color theme (blue accents)
* Organized visuals for better readability

---

## 🧠 **Insights Derived**

* Certain sub-categories such as **Binders, Phones, and Accessories** generate high profit
* Some product types consistently show low profitability
* Sales fluctuate significantly by month
* Consumer segment contributes strongly to revenue
* Geographic performance varies by state

---

## 📄 **Exported Deliverable**

The final dashboard was exported as:
✔ **PDF File: `dashboard.pdf`**

(Since online publishing required login, the PDF is used as submission.)

---

## ✅ **Conclusion**

This Power BI dashboard provides a comprehensive view of Superstore business performance.
It helps stakeholders understand trends, profitability, and customer behavior for improved decision-making.
