# 📊 Amazon Sales Report

This project focuses on analyzing Amazon sales data to uncover business trends, product performance, and operational insights. Using Python and popular data visualization libraries, we explored customer behavior, revenue patterns, and shipment performance.

---

## 📁 Dataset Overview

- **File Name:** Amazon Sale Report.csv  
- **Total Rows:** 128977 
- **Main Features:**  
  - `Category`: Product category  
  - `Amount`, `Qty`: Sales amount and quantity  
  - `Status`, `Courier Status`: Shipment information  
  - `ship-city`, `ship-state`: Shipping location  
  - `ship-service-level`: Shipping service used  
  - `Date`: Order date

---

## 🛠️ Tools & Libraries Used

- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- Jupyter Notebook / VS Code

---

## 📌 Steps Performed

1. **Data Cleaning**  
   - Removed nulls and invalid entries  
   - Converted date columns to datetime format

2. **Feature Engineering**  
   - Created new columns like `Order_Month` and `Revenue` (`Amount * Qty`)

3. **Data Visualization**  
   - Bar charts, pie charts, line plots, and scatter plots to explore patterns

4. **Insights & Recommendations**  
   - Business insights and suggestions based on trends and patterns

---

## 📈 Key Visualizations

- Product Sales by Category  
- Monthly Revenue Trend  
- Sales Distribution in Leading Month  
- Shipment Status (Delivered, Cancelled, etc.)  
- Shipping Service Level Usage  
- Revenue vs Quantity Sold  
- Top 5 Cities by Orders  

---

## ✅ Final Business Insights and Recommendations

1. April 2022 had the highest number of orders and revenue — it was a peak sales month.  
2. Shirts and T-shirts were the most in-demand product categories — they had the highest sales volume.  
3. Standard shipping service was used the most — customers preferred cost-effective delivery over faster options.  
4. Most orders were successfully delivered — shipment and courier statuses were largely positive.  
5. Inventory and staffing should be prepared in advance for upcoming peak months (especially April).  
6. Targeted promotions and discounts should be run on high-demand categories like Shirts and T-shirts.  
7. Reasons for cancelled and pending orders should be analyzed to further improve the delivery process.  
8. Logistics and delivery services should be enhanced in top cities like Mumbai, Bengaluru, and Chennai.

---