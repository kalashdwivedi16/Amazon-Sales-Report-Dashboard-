#  Amazon Sales Report – Power BI Dashboard

##  Project Overview
This project presents an **Amazon Sales Report Dashboard** built using **Microsoft Power BI**.  
The dashboard provides an interactive view of Amazon's sales performance across different categories, regions, and time periods.  
It helps uncover insights into **sales trends, profitability, and product performance**, enabling data-driven business decisions.

---

##  Objectives
- Analyze Amazon’s **sales and profit** over time.  
- Identify **top-performing categories** and **profitable states**.  
- Detect **underperforming segments** to guide business strategy.  
- Visualize key performance indicators (KPIs) such as total orders, total sales, and total profit.

---

##  Dataset Information
The dataset used for this analysis contains transactional sales data from Amazon, including:

| Column Name | Description |
|--------------|-------------|
| `Order ID` | Unique identifier for each order |
| `Order Date` | Date when the order was placed |
| `Category` | Product category (e.g., Chairs, Phones, Storage) |
| `State` | U.S. state where the sale occurred |
| `Sales` | Total sales value per order |
| `Profit` | Profit earned from the order |

---

## Dashboard Features
### 1. **Key Performance Indicators (KPIs)**
- **Total Orders:** 3,203  
- **Total Profit:** 108.42K  
- **Total Sales:** 725.46K  

### 2. **Sales Trend over Time**
A line chart showing **Sum of Sales by Order Date**, highlighting periodic spikes that indicate **seasonal demand** or **promotional events**.

### 3. **Sales by Category**
A treemap visual comparing product categories:
- Top Categories: **Chairs, Phones, Tables, Storage**
- Low-performing Categories: **Supplies, Art**

### 4. **Profit by States**
A bar chart showing profitability across U.S. states:
- **Most Profitable State:** California (~76K)
- **Least Profitable States:** Colorado (-7K), Oregon (-1K)

### 5. **Sales Progress Gauge**
A gauge visual comparing total sales (725.46K) to a target (1.45M), showing that around **50% of the target has been achieved**.

---

##  Key Insights
| Area | Insight | Recommendation |
|------|----------|----------------|
| **Sales Trend** | Sales are event-driven with periodic spikes | Run targeted campaigns during high-demand months |
| **Category Performance** | Chairs and Phones dominate sales | Focus inventory and promotions on top categories |
| **Regional Analysis** | California drives the most profit | Strengthen logistics and customer reach in top states |
| **Low-Performing States** | Colorado and Oregon show losses | Reassess pricing, shipping, and operational costs |
| **Profitability** | Profit margin ≈ 15% | Optimize costs and promote high-margin products |

---

##  Tools & Technologies Used
- **Power BI** – Data modeling, visualization, and dashboard creation  
- **Microsoft Excel** – Data preprocessing and cleaning  
- **DAX (Data Analysis Expressions)** – Calculated measures for KPIs  

---

##  How to Use
1. Download the `.pbix` file from this repository (if uploaded).  
2. Open it in **Power BI Desktop**.  
3. Explore filters, visuals, and KPIs interactively.  
4. Modify visuals or data connections as needed for your own analysis.

---

##  Project Takeaways
This Power BI dashboard demonstrates how **data visualization can transform raw data into strategic insights**.  
It highlights the importance of:
- Analyzing **sales and profit trends** for business growth,  
- Understanding **regional and product-based performance**, and  
- Using **interactive dashboards** for better decision-making.


## Author
**Kalash Dwivedi**  
Data Analytics & Business Analytics Enthusiast  
 

## 🏷️ License
This project is licensed under the **MIT License** – feel free to use and modify it with proper credit.
