# 📊 Sales Analytics Dashboard in Excel

This project focuses on analyzing sales data using **Microsoft Excel**. It includes data cleaning with Power Query, data modeling with Power Pivot, and building an interactive report/ dashboard using PivotTables and DAX measures.

The goal is to extract meaningful business insights, track KPIs, and support strategic decision-making through clean reporting.


## 🧾 Project Summary

- Cleaned raw sales data using **Power Query**
- Transformed and loaded data into a model using **Power Pivot**
- Built relationships between tables to enable powerful calculations
- Used **DAX measures** to create dynamic metrics like product , division category wise Net sales 
- Created an **interactive report** with  pivot table


---

## 🛠️ Tools & Features Used

| Tool/Concept       | Purpose                                      |
|--------------------|----------------------------------------------|
| Excel              | Main platform for data analysis              |
| Power Query        | Data cleaning and transformation (ETL)       |
| Power Pivot        | Data modeling and managing relationships     |
| DAX (Data Analysis Expressions) | Calculations and KPIs         |
| PivotTables & Charts | Visualization of metrics and trends       |
| Slicers            | Interactive filtering for dynamic reports    |


### 01. Customer Performance Report
- **Filters Added**: Region, Market (Country), Division
- **Report Content**: Shows **Fiscal Year-wise Net Sales** from **2019 to 2021**
- Includes a calculated column: **"21 VS 20"** to compare sales growth between 2020 and 2021
- Built using **PivotTables**, **Slicers**, and **Power Pivot model**
- Useful for evaluating sales trends across geography and organizational structure

![Customer Performance Report](https://github.com/ataulmaola/Excel-Analytics/blob/428ba8a29bbf71f810291756c1eef122f6443fee/01.png)



### 02. Market Performance Report vs Target
- **Filters**: Region, Division
- **Insights**: Fiscal Year-wise Net Sales from **2019 to 2021** across different Markets (Countries)
- **Highlights**:
  - Added **"21 VS 20 Net Sales"** to show absolute growth
  - Added **"% Change"** column to show percentage growth vs previous year
  - Ideal for evaluating which markets met or missed targets and by how much
![Market Performance Report](https://github.com/ataulmaola/Excel-Analytics/blob/9c2c49658647b25521fd59f5a056e9bad0291606/02.png)

### 03. Division Level Report
- **Filters**: Region, Market
- **Insights**: Fiscal Year-wise Net Sales from **2019 to 2021** for different Divisions
- **Highlights**: Includes **"21 VS 20 Net Sales"** column to monitor division performance changes year-over-year

![Division Level Report](https://github.com/ataulmaola/Excel-Analytics/blob/cd0ea9d3555f5c9349a402baf03581c6e9d08a58/03.png)

### 04. New Products in 2021
- **Filters**: Region, Market, Division (optional)
- **Insights**:
  - Displays only products introduced in the year **2021**
  - Tracks their individual **Net Sales performance**
 
![New Products in 2021](https://github.com/ataulmaola/Excel-Analytics/blob/56dbe1d3583b319e9e43d5a80a37dec085a21561/04.png)  

### 05. Top & Bottom 5 Products
- **Filters**: Region, Market, Division
- **Insights**:
  - Highlights the **top 5** and **bottom 5** performing products based on **Net Sales**
  - Helps quickly identify best-sellers and underperformers
- **Highlights**: Great for management reporting and focusing strategic efforts on product-level performance

![Top Bottom Products](https://github.com/ataulmaola/Excel-Analytics/blob/739c2e9c396f99c0b1dbf56811ccec990417c01a/05.png)  

### 06. Top 5 Countries Report
- **Filters**: Region, Division
- **Insights**: Fiscal Year-wise Net Sales from **2019 to 2021** for the **Top 5 performing Markets (Countries)**
- **Highlights**:
  - Added **"21 VS 20 Net Sales"** column to show absolute change
  - Included **"% Change"** column to highlight performance trend between 2020 and 2021
  - Useful for identifying high-potential markets for further investment or focus
![Top 5 Countries](https://github.com/ataulmaola/Excel-Analytics/blob/28b317d228d207ddfc5b22210eeae0a997326bec/06.png)
---

## 📬 Connect with Me

If you're also learning or hiring for data roles, let’s connect!

- 📧 Email: your.email@example.com
- 🔗 LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/yourname)

---

> _This repo is part of my public accountability as I grow from beginner to pro in the data world._
