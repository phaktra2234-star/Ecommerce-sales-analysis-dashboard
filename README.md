# E-commerce Sales Analysis Dashboard

## Project Overview

This project focuses on analyzing e-commerce sales data to better understand business performance, customer purchasing trends, and profit distribution across different regions.

The project combines Python, MongoDB, and Power BI to create a complete data analysis workflow. Raw data was first explored and processed using Python in Jupyter Notebook. After cleaning and analysis, the processed data was stored in MongoDB and exported into a CSV file for dashboard creation in Power BI.

The main objective of this project is to transform raw business data into meaningful insights that can support data-driven decision-making.

---

## Project Objectives

The main goals of this project are:

* Analyze overall sales and profit performance
* Identify high-performing product categories
* Compare regional profit contribution
* Explore business patterns and trends
* Create an interactive dashboard for easier analysis
* Practice the complete data analysis workflow from preprocessing to visualization

---

## Tools and Technologies

**Programming & Analysis**

* Python
* Jupyter Notebook
* Pandas

**Database**

* MongoDB

**Visualization**

* Power BI

---

## Project Structure

```text
Ecommerce-sales-analysis-dashboard
│
├── dashboard
│   └── EcommerceDashboard.pbix
│
├── notebook
│   └── Ecommerce_analysis.ipynb
│
├── images
│   └── Ecommerce_dashboard.png
│
├── data
│   └── Ecommerce_analysis.csv
│
└── README.md
```

---

## System Architecture

The project follows a data processing pipeline where raw e-commerce data is prepared, analyzed, stored, and visualized.

### Data Flow

Raw Dataset (CSV)

↓

Python / Jupyter Notebook

(Data Cleaning & Analysis)

↓

MongoDB

(Store processed data)

↓

Export processed data into CSV

↓

Power BI

(Data Visualization)

↓

Interactive Dashboard

---

## Architecture Description

### 1. Data Source

The project starts with raw e-commerce data in CSV format.

The dataset contains business-related information such as:

* Product categories
* Sales values
* Profit values
* Regional information
* Customer and transaction-related data

---

### 2. Data Processing and Analysis

Python and Jupyter Notebook were used for data preparation and analysis.

Tasks performed include:

* Importing datasets
* Exploring data structure
* Checking missing values
* Cleaning and organizing data
* Reviewing column types
* Performing analysis
* Generating business insights

---

### 3. Database Layer (MongoDB)

After preprocessing, the cleaned dataset was imported into MongoDB.

MongoDB was used to:

* Store processed records
* Manage structured data
* Organize information efficiently
* Support data handling during analysis

---

### 4. Data Export

After analysis was completed, the processed data was exported into a CSV file.

This exported file became the final source used for dashboard creation in Power BI.

---

### 5. Visualization Layer

Power BI was used to build an interactive dashboard that presents key business insights.

Dashboard features include:

* Sales by product category
* Profit distribution by region
* Total sales overview
* Total profit overview
* Regional performance comparison

---

## Dashboard Preview

### Total Sales by Product Category

This section compares sales performance across different product categories and helps identify which category generates the highest revenue.

### Profit Distribution by Region

This visualization shows how profits are distributed across different regions and highlights stronger performing areas.

### Regional Performance Analysis

The dashboard compares profit performance among regions for easier business evaluation.

### Key Performance Indicators (KPIs)

Summary cards provide a quick overview of:

* Total Sales: 2.30M
* Total Profit: 286.40K

---

## Key Insights

Some findings from the analysis include:

* Technology generated the highest sales among product categories
* Furniture and Office Supplies also contributed significantly to total revenue
* The West region generated the highest profit
* Central region had the lowest profit contribution
* Total sales reached approximately 2.30M
* Total profit reached approximately 286.40K

---

## Skills Demonstrated

This project helped demonstrate and practice:

* Data cleaning
* Data preprocessing
* Exploratory Data Analysis (EDA)
* Data storage using MongoDB
* Data visualization
* Dashboard design
* Business insight generation
* Power BI development

---

## Future Improvements

Possible future improvements for this project:

* Add customer segmentation analysis
* Include time-series trend analysis
* Create more interactive dashboard features
* Connect Power BI directly to databases

---

## Author

CHEA Sophaktra

GitHub: https://github.com/phaktra2234-star
