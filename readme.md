# Retail Intelligence & Growth Pipeline: 1M+ Transaction Analysis

### **Project Overview**
This project transforms a raw, high-volume retail dataset (1,028,761 transactions) into a strategic business intelligence asset. Using a hybrid pipeline of **SQL** for heavy lifting and **Python (Pandas/Seaborn)** for advanced analytics, I identified critical growth drivers, operational bottlenecks, and high-value customer segments.

---

### **Tech Stack**
* **Database:** MySQL (Storage and high-speed aggregation)
* **Analysis:** Python 3.11 (Pandas, NumPy)
* **Visualizations:** Seaborn & Matplotlib
* **Modeling:** RFM (Recency, Frequency, Monetary) Segmentation

---

### **📊 Key Business Insights**

#### **1. Monthly Revenue Performance**
Analyzed net revenue (Sales - Returns) across 1.02M transactions to identify key seasonality trends and a significant **growth spike in late 2011**. This trend analysis allows for better inventory forecasting ahead of peak retail seasons.

#### **2. Toxic Asset Diagnostic**
Implemented a diagnostic view of products with the highest return-to-sale ratios. By identifying "Toxic Assets" (products with return rates >15%), the business can prioritize quality control and reduce logistics losses.

#### **3. Operational Peak-Hour Heatmap**
A temporal density analysis mapping transaction volume by day and hour. 
* **Finding:** Peak traffic occurs between **10:00 AM and 3:00 PM** on weekdays.
* **Strategy:** Optimized warehouse staffing schedules and marketing email dispatch times based on these "Hot Zones."

#### **4. RFM Behavioral Segmentation**
Transformed raw customer data into actionable marketing segments using the RFM model:
* **Champions:** High-frequency, high-spend customers (Target for Loyalty Programs).
* **At Risk:** High-spend customers who haven't purchased recently (Target for Re-engagement).
* **Hibernating:** Low-value, inactive users (Minimized marketing spend).

---

#### Further Improvements Needed and Contributions
A proper dashboard using **Tableau/Power BI** is needed which will be uploaded in upcoming days. Feel free to send PRs and notifying issues.