# Python & Pandas Data Analysis

A hands-on data analysis project using Python and Pandas to work with real-world datasets.
This repository focuses on data cleaning, exploratory data analysis (EDA), data manipulation, 
visualization, and extracting meaningful business insights from data.

## 📌 Project

### Amazon Sales Data Analysis

In this project, I performed an end-to-end exploratory data analysis on an Amazon product dataset.

The analysis focuses on:

- Product pricing
- Discount percentages
- Customer ratings
- Rating counts and product popularity
- Product categories
- Customer savings
- Outlier detection
- Relationships between different numerical variables

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Data Cleaning

The dataset was inspected and cleaned by:

- Checking dataset shape and structure
- Identifying missing values
- Investigating duplicate and repeated product IDs
- Handling missing values using available evidence
- Converting price and percentage columns into numerical formats
- Validating price and discount values
- Creating analysis-specific columns

## 📊 Exploratory Data Analysis

The following analysis was performed:

- Descriptive statistics
- Mean vs. median analysis
- Category-level analysis
- Product popularity analysis
- Customer savings analysis
- Price segmentation
- Correlation analysis
- Outlier detection using the IQR method
- Distribution and skewness analysis

## 📈 Visualizations

The project includes visualizations such as:

- Price distribution histogram
- Price boxplot
- Category distribution bar chart
- Average price by category
- Price distribution with KDE
- Rating vs. popularity scatter plot
- Discount and rating analysis

## 💡 Key Insights

Some observations from the analysis:

- Product prices are strongly right-skewed, with most products concentrated in lower price ranges.
- Electronics, Computers & Accessories, and Home & Kitchen contain most of the products in the dataset.
- Product ratings are generally concentrated around 4.0–4.5.
- Discount percentage and rating show a weak negative linear relationship.
- Discounted price and rating show only a weak relationship.
- Higher rating counts do not necessarily mean higher product ratings.
- Some products have very high rating counts, making the popularity distribution strongly right-skewed.
- High monetary savings and high discount percentage represent different business perspectives.

## 📁 Repository Structure

```text
python-pandas-data-analysis/
│
├── amazon_sales_eda.ipynb
├── README.md
└── data/
    └── amazon_sales.csv
