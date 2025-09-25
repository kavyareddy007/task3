# Global Finance & Economy Dashboard

## Overview
This project presents an **interactive Power BI dashboard** that provides insights into **global economic and financial indicators**.  
The dataset includes information on GDP growth, inflation, stock indices, market capitalization, government debt, exports/imports, FDI, unemployment, credit ratings, and commodity prices (oil & gold).  

The dashboard is designed to support **financial analysis, economic monitoring, and decision-making** by visualizing key performance indicators (KPIs), trends, and comparisons across countries.

---

## Data Preparation & Transformation
Data cleaning and transformation were performed using **Power Query**:
- Converted **Date** columns into `Date/Time` format.
- Ensured numerical fields (GDP Growth %, Inflation %, Debt, FDI, Market Cap, Oil/Gold Prices) were set as **Decimal Number** type.
- Categorical fields (Country, Stock Index, Credit Rating) were set as **Text** type.
- Replaced **blank/empty values with NULL** for consistency.
- Removed **duplicates** where necessary.
- Created **calculated columns & measures** for KPIs:
  - **Average GDP Growth Rate (%)**
  - **Average Inflation Rate (%)**
  - **Total Market Capitalization**
  - **Government Debt (Total)**
  - **Oil Price (Average)**
  - **Unemployment Rate (Average by Country)**

---

## Dashboard Features

### KPI Cards
- **Average GDP Growth Rate (%)**
- **Average Inflation Rate (%)**
- **Total Market Capitalization**
- **Oil Price**
- **Government Debt**

### Charts
1. **Export vs Import Growth** – Clustered Column Chart  
   - X-axis: Country  
   - Y-axis: Export Growth % vs Import Growth %  

2. **FDI vs Current Account Balance** – Clustered Column Chart  
   - X-axis: Country  
   - Y-axis: FDI Inflows (Billion USD) & Current Account Balance  

3. **Government Debt** – Gauge Chart  
   - Displays total government debt compared to range.  

4. **Unemployment Rate by Country** – Bar Chart  
   - X-axis: Country  
   - Y-axis: Unemployment Rate %  

5. **Inflation Trend** – Line/Scatter Chart  
   - X-axis: Year  
   - Y-axis: Inflation Rate %  
   - Legend: Country  

---

## Slicers
- **Country**
- **Credit Rating**
- **Stock Index**

These slicers enable dynamic filtering across all visuals.

---

## Insights
- Compare **export vs import balance** across nations.  
- Analyze **foreign direct investment vs current account performance**.  
- Track **inflation and unemployment trends** across countries.  
- Monitor **government debt sustainability**.  
- Evaluate **financial market performance** via stock indices & market capitalization.  

---

## Tools Used
- **Power BI** – Dashboard development  
- **Power Query** – Data cleaning & transformation  


---

## Conclusion
The **Global Finance & Economy Dashboard** consolidates multiple economic and financial indicators into a **single interactive view**, enabling analysts, policymakers, and financial experts to:  
- Monitor macroeconomic trends  
- Compare countries’ performance  
- Identify risks and opportunities in global markets  

---

