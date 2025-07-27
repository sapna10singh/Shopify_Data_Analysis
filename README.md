<img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Shopify_logo_2018.svg" alt="Shopify Logo" width="120"/>


# 📊 Shopify Sales Analysis & Dashboard

This repository features a complete end-to-end data analysis and visualization project based on **Shopify e-commerce sales data**. The analysis was conducted using **Microsoft Excel** for data preparation and **Power BI** for creating a dynamic, business-ready dashboard.

The aim of this project is to help e-commerce store owners and data enthusiasts understand customer behavior, track business performance, and derive actionable insights for strategic decisions.

---

## 📂 Files Included

### 1. `Shopify Sales.xlsx`
This is the raw + cleaned dataset exported from a Shopify store. It contains:
- Order-level data: order ID, date, fulfillment status
- Product info: name, SKU, price, quantity
- Customer details: name, email, region
- Financials: total sales, taxes, discounts, returns

🔧 **Data Preparation in Excel:**
- Removed duplicates and handled missing values
- Converted dates into Excel-readable formats
- Derived columns like:
  - `Revenue = Price × Quantity`
  - `Profit = Revenue - Cost` (if cost data exists or is assumed)
- Added helper columns for time-based analysis (Month, Year, Quarter)
- Saved as a clean version for Power BI import

---

### 2. `Shopify_Sales_Report_v3.pbix`
This is the interactive **Power BI Dashboard** created from the above Excel dataset. It includes:
- Multiple pages of interactive visuals
- Filters, slicers, and drill-through features
- DAX measures and calculated columns

---

## 🧠 Step-by-Step Process

### 🔹 Step 1: Data Cleaning (in Excel)
- Imported CSV export from Shopify
- Cleaned nulls, standardized date formats
- Removed unnecessary columns (e.g., shipping address, if not used)
- Ensured all numerical columns were properly formatted
- Saved the cleaned version as `.xlsx`

### 🔹 Step 2: Power BI Setup
- Imported the cleaned Excel file into Power BI
- Created relationships between tables (if multiple sheets used)
- Built a data model with normalized dimensions (e.g., Product Table, Customer Table)

### 🔹 Step 3: DAX Measures
Created custom DAX metrics for deeper insights:
- `Total Revenue = SUM(Sales[Revenue])`
- `AOV = DIVIDE([Total Revenue], [Total Orders])`
- `Customer Retention Rate`
- `Top 5 Products by Revenue`

### 🔹 Step 4: Visuals & Dashboard Design
Pages created in the Power BI dashboard:
1. **Sales Overview**
   - Total revenue, order count, average order value
   - Trend line showing monthly performance
   - Map of revenue by region
2. **Customer Analysis**
   - New vs returning customers
   - Customer location and sales contribution
   - Top customers by lifetime value
3. **Product Performance**
   - Most sold items by quantity
   - Top grossing products by revenue
   - Category-level insights
4. **Order Insights**
   - Fulfillment and cancellation rates
   - Return patterns
   - Time to fulfillment trends

---

## 📊 Key Visualizations Used
| Visualization       | Use Case                         |
|---------------------|----------------------------------|
| Line Chart          | Monthly revenue and orders       |
| Stacked Bar Chart   | Product category performance     |
| Donut Chart         | New vs Returning customers       |
| Map                 | Sales by country/region          |
| Card Visuals        | Key KPIs (Revenue, AOV, Orders)  |
| Table + Matrix      | Drill-down of products/customers |

---

## 🎯 Business Insights Delivered
- Identified best and worst-performing products
- Analyzed customer lifetime value and return rates
- Tracked how promotions/discounts affected revenue
- Visualized growth trends and seasonal behavior
- Region-wise product demand to plan marketing campaigns

---

## 🛠 Tools & Technologies Used

| Tool         | Purpose                                |
|--------------|-----------------------------------------|
| 🟢 Microsoft Excel | Data cleaning, transformation & pre-processing |
| 🟣 Power BI        | Data modeling, DAX, visualization & dashboard |
| 🛍️ Shopify         | Data Source (Orders, Customers, Products)   |

---

## 📈 Value of This Project

- ✅ Helps Shopify merchants monitor business health
- ✅ Supports decision-making using actual customer data
- ✅ Offers ready-to-use metrics for marketing, product, and sales teams
- ✅ Demonstrates data storytelling and dashboard design skills

---

## 🧩 Future Improvements

- Live Shopify API integration for real-time data refresh
- Include inventory costs for profit analysis
- Add cohort analysis and RFM segmentation
- Predictive sales using Power BI forecasting

---

## 🙋‍♀️ About the Creator

Created by **Sapna Singh**, a data enthusiast exploring real-world business use cases in e-commerce analytics and dashboarding.  
Let’s connect and collaborate!

📫 [LinkedIn](https://www.linkedin.com) | 

---

> 💡 If you're an e-commerce business owner or data learner, clone this project, adapt it to your store's data, and build your own Shopify BI system!

