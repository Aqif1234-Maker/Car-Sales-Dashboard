# 🚗 Car Sales Analytics Dashboard

An interactive **Power BI dashboard** designed to analyze car sales data and provide insights into sales performance, pricing, brands, locations, models, transmission types, and yearly/monthly trends.

## 📊 Dashboard Preview

![Car Sales Dashboard](screenshots/dashboard.png)

---

## 🎯 Project Objective

The objective of this project is to transform raw car sales data into an interactive Power BI dashboard that helps users understand:

- Overall sales performance
- Revenue generated
- Average car price
- Brand-wise sales
- Location-wise sales
- Model-wise sales
- Transmission preferences
- Monthly sales trends
- Year-wise sales performance

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query**
- **DAX**
- **CSV Dataset**
- **Data Cleaning & Transformation**
- **Data Visualization**

---

## 📁 Dataset

The dashboard is based on a car sales dataset containing information such as:

- Sale Date
- Gender
- Annual Income
- Brand
- Model
- Transmission
- Price
- Dealer Number
- Location
- Year
- Units Sold

Customer names, phone numbers, and other unnecessary fields were removed during data preparation to keep the analysis focused on relevant sales information.

---

## 🧹 Data Preparation

The dataset was prepared using **Power Query**.

The following transformations were performed:

1. Removed unnecessary columns.
2. Renamed columns for better readability.
3. Changed columns to appropriate data types.
4. Extracted the year from the sale date.
5. Created a `Units Sold` column.
6. Created `Month Name` and `Month Number` columns.
7. Sorted months chronologically using `Month Number`.
8. Prepared the dataset for Power BI visualization.

---

## 📈 Dashboard Features

### KPI Cards

The dashboard contains the following key performance indicators:

- **Total Units Sold**
- **Average Price**
- **Total Revenue**
- **Total Brands**

### Visualizations

The dashboard includes:

- Units Sold by Brand
- Units Sold by Location
- Monthly Sales Trend
- Sales by Transmission
- Average Price by Brand
- Top Car Models by Units Sold
- Total Units Sold by Year

---

## 📊 Key Analysis

The dashboard allows users to identify:

- Which brands have the highest sales
- Which locations generate the most sales
- Which car models are most popular
- The distribution of automatic and manual vehicles
- Changes in sales throughout the year
- Changes in sales across different years
- Differences in average vehicle prices between brands

---

## 📂 Project Structure

```text
Car-Sales-Dashboard/
│
├── Car Sales Dashboard.pbix
├── README.md
│
└── screenshots/
    └── dashboard.png
