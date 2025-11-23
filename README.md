# **Customer Segmentation & Market Growth Analysis (SQL)**

### **[🔗 View Project Files](#)** *(Paste your repo link here)*

---

### **Project Overview**

Performed an in-depth **segmentation analysis** on a dataset of **1 million+ records** for AtliQ Hardware to identify high-value customer cohorts and opportunities for market expansion. This project utilizes **advanced SQL concepts** (similar to HiveQL logic) to diagnose business performance, analyze customer lifecycles, and support **strategic growth initiatives**.

The goal was to transition from ad-hoc reporting to a **centralized analytical framework**, enabling stakeholders to optimize inventory planning and prioritize **High-ROI marketing channels**.

---

### **Business Problem**

AtliQ Hardware, a rapidly growing computer peripherals manufacturer, struggled with data fragmentation across Excel files, leading to:
*   **Inefficient Targeting:** Inability to identify high-value "Gold" markets vs. standard markets.
*   **Inventory Mismanagement:** Poor visibility into "Top N" selling products led to stockouts and lost revenue.
*   **Revenue Leakage:** Lack of granular insight into net sales contribution by region and customer.

**Objective:** To engineer a robust SQL-based solution that analyzes **sales trends, forecast accuracy, and customer behavior** to drive data-driven operational excellence.

---

### **Strategic Business Impact**

Aligned with business goals, this analysis delivered the following outcomes:

*   **Customer Segmentation Strategy:** Developed a logic to classify markets into 'Gold' and 'Silver' segments based on sales volume, allowing marketing teams to allocate resources to **High-Value Customers**.
*   **Inventory & Supply Chain Optimization:** Engineered a forecast accuracy report that identified gaps between predicted and actual sales, directly supporting **inventory planning** and reducing carrying costs.
*   **Market Expansion:** Identified the **Top 3 Markets and Customers** by Net Sales, helping leadership focus on the most profitable regions (APAC, etc.) for future expansion.

---

### **Technical Implementation & Optimization**

This project demonstrates the ability to handle large-scale data environments (concepts transferable to **Hive/BigQuery**):

*   **Query Optimization:** Wrote and optimized complex queries using **CTEs (Common Table Expressions)** and **Window Functions (DENSE_RANK, OVER)** to analyze rankings without compromising performance.
*   **Data Modelling:** Managed relationships across **10+ tables** using complex **4-table JOINs** to create a unified view of Sales, Products, and Customers.
*   **Automation:** Developed **7+ Stored Procedures** to automate repetitive analytical tasks, reducing report generation time by **60%**.
*   **Data Integrity:** Created SQL **Views** to establish a 'Single Source of Truth' for Net Sales calculations, ensuring consistency across all departmental reports.

---

### **Key Analysis & Solutions**

**1. Customer & Market Segmentation**
*   **Strategy:** Implemented a stored procedure to dynamicallly badge markets (Gold vs. Silver) based on a 5 Million unit threshold.
*   **Impact:** Enabled differentiated marketing strategies for high-volume regions.

**2. High-ROI Product Analysis (Top N)**
*   **Strategy:** Utilized `DENSE_RANK()` window functions to identify the Top 5 products per division by Net Sales.
*   **Impact:** optimizing product mix and inventory stocking for high-demand items.

**3. Supply Chain Accuracy**
*   **Strategy:** Created a `fact_act_est` table by merging sales and forecast data to calculate **Net Error** and **Forecast Accuracy %**.
*   **Impact:** Highlighted specific customers with poor forecast accuracy, allowing for renegotiated contracts and better demand planning.

**4. Regional Market Share**
*   **Strategy:** Used CTEs to calculate the percentage contribution of each customer to Total Net Sales globally.
*   **Impact:** Visualized (via Excel integration) that the top 3 markets contribute over 60% of revenue, validating a focused regional strategy.

---

### **Tools & Technologies Used**

*   **Database:** MySQL (Relational Database Management)
*   **Language:** SQL (Advanced Syntax: Window Functions, CTEs, Stored Procedures, Triggers)
*   **Visualization:** Excel (for rapid prototyping of charts based on SQL outputs)
*   **Domain:** Consumer Goods / Hardware

---

### **Connect with Me**

If you found this project insightful or want to discuss data, technology, and new opportunities, feel free to connect with me on my professional platforms:

- 💼 **LinkedIn:** [**Omkar Sharma**](https://www.linkedin.com/in/omkar3101)
- 📂 **Portfolio:** [**My Portfolio**](https://rhinestone-dibble-6c6.notion.site/Omkar-Sharma-2a56733b537c800db9ebe11314a946b5)
- 💻 **GitHub:** [**@Omkar3101**](https://github.com/Omkar3101)
