# Amazon Sales Analysis using Python

## Project Overview
This project focuses on analyzing Amazon e-commerce sales data using Python to uncover key business insights such as sales trends, top-performing product categories, customer payment behavior, and geographic revenue distribution. The analysis involves data cleaning, preprocessing, exploratory data analysis (EDA), and data visualization to support data-driven decision-making.

---

## Tools & Technologies
- **Python**
- **Pandas** – Data cleaning & manipulation  
- **Matplotlib** – Data visualization  
- **CSV Dataset** – Amazon sales transactions  

---

## Dataset Description
The dataset contains Amazon order-level sales data with attributes including:
- Order date
- Product category & brand
- Quantity, unit price, discounts, taxes
- Total sales amount
- Payment method
- Order status
- Customer location (City, State, Country)

---

## Data Cleaning & Preprocessing
Key preprocessing steps performed:
- Converted `OrderDate` to datetime format with error handling
- Ensured numeric columns were correctly typed
- Standardized categorical values (case formatting, whitespace removal)
- Removed duplicate records
- Filtered out cancelled orders to focus on completed sales
- Engineered new time-based features (Year, Month, Quarter)
- Exported a clean dataset for analysis and visualization

---

## 📈 Exploratory Data Analysis (EDA)

### 1️⃣ Monthly Sales Trend
- Analyzed total monthly revenue to identify seasonal sales patterns
- Visualized trends using a line chart to observe growth and fluctuations

### 2️⃣ Top Product Categories by Sales
- Identified the top 10 revenue-generating product categories
- Highlighted the top 3 categories contributing the highest sales
- Used bar charts with data labels for clarity

### 3️⃣ Payment Method Distribution
- Analyzed customer payment preferences
- Visualized percentage and count distribution using a pie chart

### 4️⃣ Geographic Sales Analysis
- Evaluated country-wise sales performance
- Displayed revenue contribution using a horizontal bar chart

---

## Visualizations Included
- Line Chart: Monthly Sales Trend  
- Bar Chart: Top 10 Product Categories (Top 3 Highlighted)  
- Pie Chart: Payment Method Distribution (Value & Percentage)  
- Horizontal Bar Chart: Sales by Country  

---

## Key Insights
- A small number of product categories contribute a significant share of total revenue
- Sales show clear monthly trends, indicating seasonality
- Certain payment methods dominate customer transactions
- Revenue concentration varies significantly by country

---

## Project Structure
├── Amazon (1).csv # Raw dataset
├── Amazon_Cleaned.csv # Cleaned dataset
├── amazon_sales_analysis.py # Python analysis script
├── README.md # Project documentation


---

## Future Enhancements
- Add interactive dashboards using Streamlit or Power BI
- Perform customer segmentation analysis
- Implement forecasting for future sales trends

---

## Author
**Devi Smita**  
Data Analyst | Python | SQL | Power BI  

🔗 LinkedIn: *([profile](https://github.com/Devi27-create/Amazon_Sales_Analysis/edit/main/README.md))*  
🔗 GitHub: *([this repository](https://github.com/Devi27-create/Amazon_Sales_Analysis/edit/main/README.md))*  
