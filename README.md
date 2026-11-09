# 🛒 BazaarLens PK – Pakistan Grocery Price Intelligence & City-Level Analysis

## 📌 Project Overview

**BazaarLens PK** is a Data Analytics portfolio project focused on analyzing grocery prices across different cities of Pakistan.

The project combines grocery price data from Kaggle and the Pakistan Bureau of Statistics (PBS) to explore city-wise price differences, item-level pricing patterns, weekly price movements, and the cost of a selected grocery basket.

The goal is to transform raw grocery price data into meaningful insights that can help consumers understand price variations and support better data-driven decisions.

---

## 🎯 Project Objectives

- Analyze grocery prices across different cities of Pakistan.
- Identify cities with the highest and lowest average grocery prices.
- Compare prices of different grocery items.
- Explore weekly price movements using PBS data.
- Analyze monthly and yearly price changes where available.
- Calculate and compare the cost of a selected grocery basket across cities.
- Create meaningful visualizations to communicate findings.
- Develop practical recommendations based on the analysis.

---

## 📂 Datasets Used

This project uses three datasets:

### 1. Kaggle – Pakistan City Wise Grocery Price 2025

- Contains grocery prices collected from five Pakistani cities.
- Includes 350 records and 15 grocery items.
- Covers city, item, brand, price, collection date, and market/source information.
- Collection date: April 28, 2025.

### 2. PBS – Monthly Price Data

- Contains monthly grocery price information for 51 items across 17 cities.
- Includes city-level prices and monthly/yearly comparison fields.
- Used for city-wise price analysis and monthly/yearly price change analysis.
- Represents a September 2026 snapshot.

### 3. PBS – Weekly Price Data

- Combines five weekly PBS reports.
- Covers October 1, 8, 15, 22, and 29, 2026.
- Contains 255 item-date records across 17 cities.
- Used to analyze weekly price movements and national average price trends.

---

## 🛠️ Tools & Technologies

The following tools and Python libraries were used:

- **Python** – Data analysis and programming.
- **NumPy** – Numerical operations.
- **Pandas** – Data cleaning, manipulation, and analysis.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **Plotly Express** – Interactive visualizations.
- **Jupyter Notebook** – Analysis environment.
- **VS Code** – Project development environment.

---

## 📁 Project Structure

```text
BazaarLens PK/
│
├── Datasets/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Exploratory_Data_Analysis.ipynb
│   ├── 04_City_Wise_Analysis.ipynb
│   ├── 05_Time_Series_Analysis.ipynb
│   ├── 06_Grocery_Basket_Analysis.ipynb
│   ├── 07_Data_Visualization.ipynb
│   └── 08_Final_Insights.ipynb
│
├── visualizations/
│   ├── Kaggle/
│   ├── PBS_Monthly/
│   ├── PBS_Weekly/
│   └── Grocery_Basket/
│
├── reports/
│   ├── BazaarLens_PK_Final_Report.pdf
│   ├── BazaarLens_PK_Executive_Summary.pdf
│   └── BazaarLens_PK_Key_Findings.xlsx
│
└── README.md
```

---

## 🔍 Project Workflow

The project was completed in eight analytical stages:

| Notebook | Description |
|---|---|
| 01 – Data Understanding | Inspected datasets, columns, data types, and structure. |
| 02 – Data Cleaning | Handled data types, column names, missing values, and data quality checks. |
| 03 – Exploratory Data Analysis | Explored price distributions, item-level patterns, and descriptive statistics. |
| 04 – City-Wise Analysis | Compared grocery prices across Pakistani cities. |
| 05 – Time Series Analysis | Explored weekly grocery price movements using PBS data. |
| 06 – Grocery Basket Analysis | Compared the cost of a selected grocery basket across cities. |
| 07 – Data Visualization | Created visual representations of important findings. |
| 08 – Final Insights | Summarized findings, recommendations, and project limitations. |

---

## 📊 Key Findings

### Kaggle Dataset

- Islamabad had the highest average grocery price among the five cities, at approximately **Rs. 350.33**.
- Karachi had the lowest average, at approximately **Rs. 312.41**.
- Eggs (Dozen) had the highest average item price, while Moong Dal had the lowest average item price in the dataset.
- No price outliers were detected using the applied IQR method.

*Note: Item prices may use different measurement units, so direct comparisons should be interpreted carefully.*

### PBS Monthly Dataset

- Islamabad had the highest city-level average price, approximately **Rs. 779.92**.
- Bannu had the lowest city-level average, approximately **Rs. 674.84**.
- The dataset helped identify relatively expensive and affordable cities and items.

### PBS Weekly Dataset

- Islamabad had the highest average price across the analyzed weekly data, approximately **Rs. 804.21**.
- Sukkur had the lowest average, approximately **Rs. 698.99**.
- Chicken Farm Broiler (Live) recorded an approximately **18.02% increase** over the analyzed period.
- Wheat Flour Bag (20 Kg) recorded an approximately **9.42% increase**.
- Milk prices increased slightly, while Rice Basmati Broken recorded a small decrease.

### Grocery Basket Analysis

A selected basket of 11 grocery items was compared across 17 cities.

- Islamabad had the highest basket cost: **Rs. 8,226.68**.
- Faisalabad had the lowest basket cost: **Rs. 7,164.49**.
- The difference between the highest and lowest basket costs was **Rs. 1,062.19**.

*Note: This is a selected 11-item basket, not the complete monthly grocery expenditure of a household.*

---

## 📈 Visualizations

The project includes visualizations for:

- Top expensive grocery items.
- City-wise average grocery prices.
- Monthly and yearly price increases.
- Weekly national average price trends.
- Selected grocery item price movements.
- Most expensive and cheapest grocery basket cities.

All generated charts are organized into separate folders under `visualizations/`.

---

## 💡 Business Recommendations

Based on the analysis:

1. Consumers can compare grocery prices across cities before making purchasing decisions.
2. Retailers can monitor weekly price movements to improve purchasing and inventory planning.
3. Analysts can use city-level comparisons to identify regional price differences.
4. Frequently increasing grocery items can be monitored for better budgeting and planning.
5. Future analysis can incorporate more frequent and extensive data to identify longer-term patterns.

---

## ⚠️ Project Limitations

- The Kaggle dataset represents a single collection date.
- The PBS monthly dataset represents one monthly snapshot for the analyzed period.
- The PBS weekly dataset covers only five weeks.
- Missing values in selected PBS records were retained where appropriate.
- The selected grocery basket contains only 11 items.
- The analysis does not represent the complete household cost of living or official inflation measurement.
- Different grocery items may have different units of measurement.

---

## 🚀 Future Improvements

Potential future enhancements include:

- Adding more historical grocery price data.
- Expanding the analysis to additional cities and grocery items.
- Building an interactive dashboard using Power BI or Tableau.
- Developing price prediction models using Machine Learning.
- Automating regular data collection and updates.
- Creating a more comprehensive household grocery basket.

---

## 📄 Project Reports

The `reports/` folder contains:

- **Final Project Report (PDF):** Detailed documentation of the project and findings.
- **Executive Summary (PDF):** A concise overview of the project.
- **Key Findings (Excel):** Organized analytical results and comparisons.

---

## 👨‍💻 Author

**Mohsin Saleem**

Data Analytics Portfolio Project

**Project:** BazaarLens PK – Pakistan Grocery Price Intelligence & City-Level Analysis

---

## ⭐ Conclusion

BazaarLens PK demonstrates how Python-based data analytics can transform grocery price datasets into meaningful insights.

By combining Kaggle and PBS data, the project explores grocery price differences, city-level comparisons, weekly price movements, and selected grocery basket costs across Pakistan.

This project represents an end-to-end data analytics workflow, from data understanding and cleaning to exploratory analysis, visualization, and insight generation.
