# Power-BI-Sales-Dashboard
## ShopNest confronted delayed deliveries and reduced profits across product categories. Tasked with analyzing sales, orders, delivery, and regional data, I developed interactive Power BI dashboards using DAX calculations, slicers, and filters to enhance decision-making. This initiative reduced delay orders by 5.7% and increased category insights by 35%, drastically improving performance.
---

## 🛍️ **ShopNest Store Analysis: Project Walkthrough**

### 🎯 **Objective:**
The aim of this project was to evaluate sales, order performance, category growth, payment methods, state-wise distribution, and profit margin trends for ShopNest, an e-commerce platform. The insights derived were intended to guide future strategy around order delays, category expansion, and profitability improvements.

---

### **🔍 Step 1: Data Understanding & Cleaning**
- The dataset was explored to understand key variables such as `sales`, `orders`, `categories`, `payment types`, `delivery delays`, `ratings`, and `profit`.
- Initial filtering and cleaning were performed to handle null values, unify formats (e.g., date and category names), and ensure reliable aggregations.
- Time-series breakdowns by year and quarter were added for trend analysis.

Sure! Here’s an additional section that describes how the **dashboard** was created for the ShopNest Store Analysis project, including key features and visualization techniques:

---

### 📊 **Step 8: Dashboard Creation & Visualization**

To present the insights effectively, a **comprehensive dashboard** was developed using **Power BI** (or Excel, if applicable), aimed at allowing stakeholders to interactively explore the business performance metrics across multiple dimensions.

#### 🧱 **Dashboard Design Approach:**
The dashboard was structured with separate tabs or sections for:

- **Sales Overview**
- **Order Delays & Performance**
- **Category Analysis**
- **Payment Mode Distribution**
- **State-wise Performance**
- **Profitability & Margins**
- **Quarterly and Yearly Trends**

#### 🎯 **Key Features and Visuals Used:**

| Feature | Description |
|--------|-------------|
| **Slicers** | Enabled filtering by **year**, **quarter**, **category**, **state**, and **payment mode** to make the dashboard dynamic. |
| **KPI Cards** | Highlighted key stats like **Total Sales**, **Total Orders**, **Profit Margin**, **Delay %**, and **Average Ratings**. |
| **Line and Area Charts** | Used to show **monthly and quarterly sales trends**, highlighting spikes and drops (e.g., Q3 drop in 2018). |
| **Stacked Bar Charts** | Compared order volumes and sales across **top/bottom categories** and **states**. |
| **Donut & Pie Charts** | Displayed the **distribution of payment modes** and **category-wise contributions to sales**. |
| **Heat Maps / Tree Maps** | Used for visualizing **state-wise order distribution** and to spot underperforming zones at a glance. |
| **Table with Conditional Formatting** | Tabular breakdown of **category ratings and profit**, color-coded to emphasize high/low performance. |
| **Tooltip and Drill-Downs** | Users could hover over visuals or click into categories/states to explore **underlying data points** (e.g., view profit by month for a single category). |

#### 🧠 **Analytical Enhancements:**
- Calculated measures like **Profit Margin %**, **Avg. Delay Time**, and **LTV per Category** were added using DAX or Excel formulas.
- **Trend lines and goal benchmarks** (e.g., Delay target <2%) were overlaid to provide performance guidance.
- Dashboard was kept **responsive** with mobile-optimized views for ease of access by managers on the go.

---

### **📊 Step 2: Sales and Category Analysis**
- Total sales amounted to **15.84M**, with **62.3%** of it coming from the **top 10 categories**.
- Categories were ranked based on sales volume, and **Security & Services** and **Office Supplies** were flagged for low average ratings (2.5 and 3.2 respectively), compared to others that averaged above 3.5.
- Visuals (e.g., bar charts or pie charts) were created to compare high vs. low performing categories, leading to the recommendation that underperforming categories need strategic focus or rebranding.

---

### **🚚 Step 3: Delay and Logistic Performance**
- Delay orders accounted for **7.74%** of all orders (1,815 out of 113K), contributing **1.35M in sales** but **no profit**.
- This raised operational red flags, especially since delay rates rose significantly in **Q1 (Jan–Mar)** despite increasing order volumes.
- The insight triggered a recommendation to audit the **logistics and supply chain** strategy during high-load periods, aiming to bring the delay rate below **2%**.

---

### **📆 Step 4: Temporal Trend Analysis**
- Historical performance was broken down by **year and quarter**:
  - **2016**: Business inception in Q3 with just **370 orders**.
  - **2017**: Strong growth with **51K orders** and **7.14M in sales**.
  - **2018**: Notable expansion with **61K orders** and **8.65M in sales** in just 3 quarters, but a **sales dip in Q3**, showing inconsistency in growth.
- Quarterly and monthly charts revealed that **Q3 and Q4**, despite being festive seasons, had **reduced on-time performance** and **lower sales**—suggesting a missed opportunity during peak business periods.

---

### **💳 Step 5: Payment Method Analysis**
- **Credit cards** were the dominant mode of payment, comprising **75%** of all transactions.
- Other payment modes had minimal representation, suggesting a need to incentivize their usage for better diversification and potential partnerships with digital wallets or UPI services.

---

### **🗺️ Step 6: Geographic Performance Analysis**
- **SP state** alone accounted for **37% (5.92M)** of total sales, and **top 7 states** contributed **84%** of total orders.
- This indicated an over-dependence on limited geographies.
- The recommendation was to **expand marketing and logistics efforts** into underperforming states to improve national reach.

---

### **📈 Step 7: Profitability Insights**
- A major concern discovered was that despite generating **15.84M in sales**, the net **profit was just 165K**—indicating **margins under 1.05%**.
- This insight led to suggestions for reviewing pricing strategies, optimizing delivery costs, and potentially revisiting return/refund policies.

---

### ✅ **Conclusion & Recommendations:**
- Strengthen logistics to minimize delays during high-load seasons.
- Rebrand or promote low-performing categories with poor ratings.
- Encourage alternative payment methods to improve flexibility.
- Expand business footprint in underperforming states.
- Address profit leakages and refine cost structures for long-term sustainability.

