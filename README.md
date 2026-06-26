# Task 2: Exploratory Data Analysis (EDA) & Business Intelligence

## Overview

This project performs Exploratory Data Analysis (EDA) on the **ApexPlanet Data Analytics Dataset** using Python. The objective is to understand the dataset, identify missing values, generate statistical insights, and visualize sales trends using charts.

## Technologies Used

* Python
* Pandas
* Matplotlib

## Dataset

**File:** `ApexPlanet_DataAnalytics_Dataset.xlsx`

The dataset contains customer and sales-related information such as:

* Customer Age
* City
* Product Category
* Total Sales
* Other business-related attributes

## Features Implemented

### 1. Data Loading

* Reads the Excel dataset using Pandas.
* Displays the first five records.

### 2. Data Inspection

* Checks for missing values.
* Displays dataset information.
* Generates statistical summaries.

### 3. Business Metrics

* Calculates total sales.
* Calculates average customer age.

### 4. Sales Analysis

* Sales by Category
* Sales by City

### 5. Data Visualization

The project generates the following visualizations:

* Bar Chart: Sales by Category
* Pie Chart: Category-wise Sales Distribution
* Histogram: Age Distribution of Customers

## Code Workflow

1. Import required libraries.
2. Load dataset from Excel file.
3. Display dataset preview.
4. Check data quality and missing values.
5. Generate descriptive statistics.
6. Calculate business KPIs.
7. Analyze sales performance by category and city.
8. Visualize findings using charts.

## Sample Output

### Business Insights

* Total Sales generated from all transactions.
* Average customer age.
* Best-performing product categories.
* Top-performing cities by sales.

### Visualizations

* Category Sales Bar Chart
* Category-wise Sales Pie Chart
* Customer Age Distribution Histogram

## How to Run

1. Install required libraries:

```bash
pip install pandas matplotlib openpyxl
```

2. Place the dataset file in the project folder:

```text
ApexPlanet_DataAnalytics_Dataset.xlsx
```

3. Run the Python script:

```bash
python task2_eda.py
```

## Learning Outcomes

* Data Exploration using Pandas
* Business Intelligence Analysis
* Data Visualization with Matplotlib
* Extracting Insights from Real-World Datasets

