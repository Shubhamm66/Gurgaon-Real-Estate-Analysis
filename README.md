# Gurgaon Real Estate Market Analysis

**A Data Analysis Project using Python, Pandas, Matplotlib and Seaborn**

## 📌 Project Overview

This project explores the Gurgaon real estate market using Python. The objective is to clean property listing data and analyze property prices, localities, area, BHK configurations, property types, RERA approval status and builders.

The project uses data cleaning, exploratory data analysis (EDA), aggregation and data visualization to understand property pricing patterns and compare different segments of the real estate market.

## 🎯 Project Objectives

- Clean and prepare property listing data for analysis.
- Identify the costliest property in the dataset.
- Find localities with the highest average property prices and price per square foot.
- Compare ready-to-move and under-construction properties.
- Analyze average prices for RERA-approved and non-approved properties.
- Compare price per square foot across BHK configurations and property types.
- Identify builders with the highest average price per square foot.
- Explore the relationship between property area and price per square foot.

## 🛠️ Tools and Technologies

- **Python** – Data analysis and scripting
- **Pandas** – Data cleaning, grouping, and aggregation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook / Python IDE** – Code execution environment

## 📂 Project Files

| File | Description |
|---|---|
| `main.py` | Python script for data cleaning, analysis, and visualization |
| `data.csv` | Property dataset used for analysis |
| `Gurgaon_Real_Estate_Market_Analysis_PPT.pptx` | Project presentation |

## 📊 Dataset Description

The project analyzes property listing data for the Gurgaon real estate market. The dataset contains fields used to study property prices, locations, property configurations, and builder-related pricing patterns.

Key columns used in the analysis include:

- `price` – Property price
- `area` – Property area
- `rate_per_sqft` – Price per square foot
- `locality` – Property location
- `bhk_count` – Number of bedrooms, halls, and kitchens
- `status` – Property construction or possession status
- `rera_approval` – RERA approval information
- `flat_type` – Property type
- `society` – Society name
- `company_name` – Builder or company name

## 🧹 Data Cleaning and Preparation

The following steps are performed in the Python script:

1. Loaded the dataset using Pandas.
2. Standardized column names by removing extra spaces, converting them to lowercase, and replacing spaces with underscores.
3. Removed duplicate records.
4. Cleaned numerical columns by removing commas from `price`, `area`, and `rate_per_sqft`.
5. Converted numerical columns to appropriate numeric data types.
6. Standardized categorical values in `status`, `rera_approval`, and `flat_type`.
7. Converted RERA approval values into Boolean values (`True` and `False`).
8. Removed duplicate records again after cleaning.

These steps prepare the dataset for consistent grouping, comparison, and analysis.

## 🔎 Exploratory Data Analysis

The project addresses the following 10 business questions:

### 1. Which is the costliest flat in the dataset?
Identifies the property with the maximum price and displays its BHK configuration, locality, price in crores, and society name.

### 2. Which locality has the highest average price?
Groups properties by locality and identifies the locality with the highest average property price.

### 3. Which locality has the highest rate per square foot?
Calculates the average price per square foot for each locality and identifies the highest one.

### 4. Do ready-to-move properties cost more than under-construction properties?
Compares average prices for ready-to-move and under-construction properties.

### 5. Do RERA-approved properties command a price premium?
Compares average property prices for RERA-approved and non-approved properties to examine whether approval is associated with a higher average price.

### 6. How does area impact price?
Includes a scatter plot of property area against property price. The plotting code is currently commented out in `main.py`.

### 7. Which BHK configuration is most expensive based on price per square foot?
Groups properties by BHK count and identifies the configuration with the highest average price per square foot.

### 8. Which property type is the costliest?
Compares average price per square foot across property types.

### 9. Do certain builders price higher?
Ranks builders by their average price per square foot and displays the top five builders.

### 10. Are larger homes more expensive per square foot?
Uses a scatter plot to explore the relationship between property area and price per square foot.

## 📈 Data Visualization

The project uses Seaborn and Matplotlib to visualize property pricing patterns.

**Scatter plot: Area vs. Price per Square Foot**

The current script plots `area` on the x-axis and `rate_per_sqft` on the y-axis. This helps explore how price per square foot varies across properties of different sizes.

The area-versus-total-price scatter plot is included in the code as a commented-out section and can be enabled when needed.

## ⚙️ How to Run the Project

### Prerequisites

Install Python and the required libraries.

```bash
pip install pandas matplotlib seaborn
```

### Steps

1. Clone or download this repository.
2. Keep `main.py` and `data.csv` in the same folder.
3. Open a terminal in the project folder.
4. Run the Python script:

```bash
python main.py
```

5. Review the analysis results printed in the terminal.
6. View the scatter plot generated by the script.

**Note:** The script expects the CSV file to contain the column names used in the code. Make sure the dataset is available in the same directory before running the project.

## 💡 Key Analysis Areas

This project demonstrates practical data analysis skills through:

- Data cleaning and duplicate removal
- Numerical and categorical data preparation
- Grouping and aggregation with Pandas
- Average price and price-per-square-foot comparisons
- Conditional comparisons between property categories
- Builder ranking using aggregated results
- Scatter plot visualization

The actual findings depend on the values in `data.csv` and can be verified by running `main.py`.

## 📽️ Project Presentation

The project presentation is available in the repository:

[View Gurgaon Real Estate Market Analysis Presentation](Gurgaon_Real_Estate_Market_Analysis_PPT.pptx)

## ✅ Conclusion

This project demonstrates how Python can be used to clean real estate data and investigate property pricing patterns. By analyzing locality, property area, BHK configuration, construction status, RERA approval, property type and builder information, the project provides a structured approach to exploring the Gurgaon real estate market.

It showcases practical skills in data preparation, exploratory data analysis, Pandas operations and data visualization relevant to an entry-level Data Analyst role.

## 👨‍💻 Author

**Shubham Modokar**

- GitHub: [Shubhamm66](https://github.com/Shubhamm66)
- LinkedIn: [Shubham Modokar](https://linkedin.com/in/shubham-modokar)

