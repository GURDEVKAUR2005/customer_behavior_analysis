# customer_behavior_analysis
## Overview
This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI. The goal is to extract meaningful insights from raw data by performing data cleaning, exploratory data analysis (EDA), SQL analysis, and data visualization.
The workflow starts with loading the dataset in Python, preparing and cleaning the data, performing analytical queries using MySQL, and finally creating an interactive dashboard in Power BI. The results are summarized in a report and presentation.

## Dataset
The dataset contains customer shopping information such as:
- Customer ID
- Gender
- Age
- Category of product
- Item purchased
- Purchase amount
- Review rating
- Location
- Payment method
- Frequency of purchases

## Tools & Technologies
The following tools were used in this project:
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
- SQL
- MySQL
- Visualization
- Power BI
- Presentation & Reporting
- Gamma (for presentation)
- PowerPoint
- Jupyter Notebook

## Project Workflow
1. Data Loading
The dataset is loaded into Python using Pandas for initial exploration.

2. Exploratory Data Analysis (EDA)
EDA was performed to understand the structure and patterns in the dataset, including:
- Data distribution
- Missing values
- Outliers
- Customer behavior patterns

3. Data Cleaning

Data cleaning steps included:
-- Handling missing values
-- Fixing data types
-- Removing duplicates
-- Standardizing column values

4. SQL Analysis

The cleaned dataset was imported into MySQL, where SQL queries were used to analyze:
- Top selling products
- Average product ratings
- Category-wise sales
- Customer purchase behavior
- Most popular items

5. Dashboard Creation

A Power BI dashboard was created to visually represent key insights.

The dashboard includes:
-Sales by category
- Top purchased items
- Customer demographics
- Rating analysis
- Purchase trends

6. Reporting

Insights from the analysis were summarized in a data analytics report and a presentation created using Gamma and PowerPoint,
Dashboard
The Power BI dashboard provides an interactive view of:
- Customer purchase trends
- Product category performance
- Top rated products
- Customer demographic insights

This helps in understanding which products perform best and how customers behave while shopping.

# Key Results

Some of the insights derived from the analysis include:
- Identification of the top selling products
- Understanding customer purchase patterns
- Discovering categories with highest revenue
- Analysis of average product ratings
- Insights into customer demographics and preferences

## How to Run the Project
1. Clone this repository
git clone https://github.com/yourusername/data-analytics-project.git

2. Install required Python libraries
pip install pandas numpy matplotlib seaborn mysql-connector-python

3. Run the Jupyter Notebook for data analysis
jupyter notebook

4. Import the dataset into MySQL and run the SQL queries provided in the project.
Open the Power BI dashboard file (.pbix) to explore the visualizations.

## Project Structure
data-analytics-project
│
├── dataset
│   └── customer_shopping_behavior.csv
│
├── notebooks
│   └── eda_analysis.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── report
│   └── project_report.pdf
│
└── README.md
