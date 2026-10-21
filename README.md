# Online Retail — Exploratory Data Analysis

## 📌 Project Overview

This project presents an Exploratory Data Analysis (EDA) of an Online Retail dataset using Python. The analysis focuses on understanding sales performance, customer behavior, product performance, geographical distribution, and sales trends over time.

The project was completed as part of my **DecodeLabs Data Analytics Internship — Task 2**.

---

## 🎯 Objectives

- Clean and prepare the retail dataset for analysis
- Identify missing values and duplicate records
- Analyze returned and unusual transactions
- Calculate sales and key business metrics
- Identify top-performing products
- Identify high-value customers
- Analyze sales across different countries
- Examine monthly sales and transaction trends
- Detect and investigate potential outliers
- Generate actionable business insights and recommendations

---

## 🔍 Key Business Questions

1. Which countries generate the highest sales?
2. Which products generate the highest revenue?
3. Which products are sold in the highest quantities?
4. How do sales change over time?
5. Which customers contribute the most revenue?
6. What is the average transaction value?
7. Are there unusual or extreme transactions?
8. What business actions can be recommended based on the findings?

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Google Colab** — Development environment
- **GitHub** — Project version control and portfolio

---

## 📊 Analysis Performed

### 1. Data Understanding & Cleaning

- Dataset structure and dimensions
- Data types and descriptive statistics
- Missing-value analysis
- Duplicate-record analysis
- Identification of returned transactions
- Filtering invalid quantities and prices

### 2. Sales Analysis

A `SalesAmount` feature was calculated using:

`SalesAmount = Quantity × UnitPrice`

The analysis examined overall sales performance and transaction values.

### 3. Country Analysis

Sales were analyzed across countries to identify the markets contributing the most revenue.

### 4. Product Analysis

Products were analyzed based on:

- Total sales revenue
- Total quantity sold

### 5. Time-Based Analysis

Monthly sales and transaction volumes were analyzed to identify trends and seasonal patterns.

### 6. Customer Analysis

Customers were ranked according to their total sales contribution to identify high-value customers.

### 7. Outlier Analysis

Extreme transaction values and unusually large quantities were investigated using statistical analysis rather than automatically removing them.

---

## 📈 Key Visualizations

The project includes visualizations for:

- Sales distribution by country
- Top 10 products by sales
- Top 10 products by quantity
- Monthly sales trend
- Monthly transaction trend
- Top 10 customers by sales
- Average transaction value by month

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| **Total Sales** | **£10,642,110.80** |
| **Total Transactions** | **19,960** |
| **Unique Products** | **4,026** |
| **Unique Countries** | **38** |
| **Unique Customers** | **4,338** |
| **Average Transaction Value** | **£20.28** |
| **Average Quantity per Transaction** | **10.62 units** |

---

## 💡 Key Findings

- The **United Kingdom** was the dominant market and generated the majority of total sales.
- **November 2011** recorded the highest monthly sales.
- **REGENCY CAKESTAND 3 TIER** was among the highest-performing products by sales.
- A small group of customers contributed significantly to total revenue.
- The dataset contains highly skewed transaction values and several extreme observations.
- Some unusually large quantities had a significant effect on product-level analysis.
- Sales performance varied considerably across countries and months.

---

## 💼 Business Recommendations

1. **Strengthen the UK market** by maintaining product availability and customer retention strategies.
2. **Expand international markets** through targeted marketing in countries showing strong sales potential.
3. **Focus on high-performing products** when planning inventory and promotional campaigns.
4. **Monitor high-value transactions** to distinguish genuine bulk purchases from potential data-quality issues.
5. **Retain high-value customers** through personalized offers and loyalty strategies.
6. **Use historical monthly trends** to improve inventory, marketing, and seasonal planning.

---

## 📁 Project Structure

```text
Online-Retail-EDA/
│
├── Online_Retail_EDA.ipynb
└── README.md
