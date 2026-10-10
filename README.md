# Pandas Analyzer & Data Visualization

A Python-based data analysis project designed to explore, clean, analyze, and visualize sales data using powerful data science libraries.

## 📌 Project Overview

**Pandas Analyzer & Data Visualization** is a menu-driven Python application that simplifies sales data analysis through an interactive command-line interface. It allows users to explore datasets, perform data manipulation, handle missing values, generate descriptive statistics, and create meaningful visualizations.

The project uses a sample sales dataset to demonstrate practical applications of Python, Pandas, NumPy, Matplotlib, and Seaborn in data analysis.

## ✨ Features

- **Data Exploration:** View the first and last five records, column names, data types, dataset information, missing values, and duplicate records.
- **DataFrame Operations:** Search product categories, sort records by profit, filter sales by country, group sales data, and generate pivot tables.
- **NumPy Operations:** Convert numerical columns into arrays, perform calculations, and analyze average profit.
- **Missing Data Handling:** Identify missing values, fill missing numerical values with the mean, remove incomplete rows, or replace missing values with zero.
- **Descriptive Statistics:** Calculate mean, standard deviation, minimum, and maximum values for numerical columns.
- **Interactive Data Visualization:** Generate seven types of charts to understand sales trends and business performance.
- **Save Visualizations:** Export generated charts as high-resolution PNG images for reports and presentations.

## 📊 Visualizations

The application supports the following visualization types:

| Visualization | Purpose |
|---|---|
| Bar Plot | Compare profit across product categories |
| Line Plot | Analyze revenue trends over time |
| Scatter Plot | Examine the relationship between quantity and profit |
| Pie Chart | Understand revenue distribution across countries |
| Histogram | Analyze the distribution of profit |
| Stack Plot | Visualize revenue across product categories |
| Seaborn Heatmap | Compare profit across countries and product categories |

Generated visualizations can be saved in the `outputs` directory.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations and statistical calculations
- **Matplotlib** — Data visualization and chart generation
- **Seaborn** — Heatmap visualization

## 📁 Project Structure

The project is organized into the following directories and files:

- `main.py` — Main application containing the data analysis features and interactive menu.
- `data/` — Contains the sample sales dataset in CSV format.
- `outputs/` — Stores generated visualizations and chart images.
- `README.md` — Project documentation.

## ⚙️ Installation and Setup

### Prerequisites

Ensure that Python is installed on your system. Basic knowledge of Python and data analysis is helpful for understanding the project.

### Setup Instructions

1. Download or clone the project repository.
2. Open the project folder in your preferred code editor or terminal.
3. Install the required Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.
4. Ensure the sample dataset is available in the `data` directory.
5. Run the application using Python.
6. Follow the interactive menu to explore data, perform operations, generate statistics, and create visualizations.

## 📂 Dataset Description

The project uses a sample sales dataset containing information about orders, customers, products, pricing, discounts, revenue, and profit.

Key dataset attributes include:

- Order ID and order date
- Customer ID and product ID
- Product category and product price
- Discount percentage and quantity
- Customer country and traffic source
- Payment method and shipping cost
- Customer rating and return status
- Discounted price, revenue, and profit

This dataset enables practical exploration of sales performance and business-related data patterns.

## 🎯 Learning Outcomes

Through this project, I explored and applied:

- Data loading and preprocessing using Pandas
- Data filtering, sorting, grouping, and aggregation
- Missing-value treatment and data quality checks
- Numerical calculations using NumPy
- Descriptive statistical analysis
- Data visualization using Matplotlib and Seaborn
- Saving visual outputs for further analysis
- Organizing a Python project into a clear structure

## 🚀 Future Enhancements

Potential improvements for future versions include:

- Interactive dashboards using Streamlit
- Advanced sales and profitability reports
- Additional charts and customizable filters
- Automated data cleaning and validation
- Exporting analysis summaries to Excel and PDF
- Support for uploading custom CSV datasets

## 👩‍💻 Author

**Sharma Shivaji**

## 📄 License

This project is intended for educational and portfolio purposes. A formal open-source license can be added if the project is distributed for reuse.
