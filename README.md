# google-play-store-data-analysis
Exploratory Data Analysis of Google Play Store applications using Python, NumPy, Pandas, Matplotlib, Seaborn, and Plotly. Includes data cleaning, statistical analysis, interactive visualizations, and feature engineering.
# Google Play Store Apps – Data Analysis

## Project Overview

This project focuses on analyzing Google Play Store applications using Python and popular data analysis and visualization libraries. The objective is to explore app ratings, categories, reviews, installations, pricing, and other attributes to identify meaningful patterns and insights.

The project covers the complete data analysis workflow, starting from dataset collection and preprocessing to exploratory data analysis, visualization, feature engineering, and final conclusions.

## Objectives

- Explore and understand the Google Play Store dataset.
- Perform numerical operations using NumPy.
- Analyze and manipulate data using Pandas.
- Clean missing values, duplicate records, and inconsistent data.
- Perform Exploratory Data Analysis (EDA).
- Create static and interactive visualizations.
- Engineer meaningful features from existing data.
- Apply categorical encoding and numerical scaling.
- Identify trends, relationships, and insights from the dataset.

## Dataset Information

- **Dataset Name:** Google Play Store Apps
- **Source:** [Kaggle – Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Format:** CSV
- **Records:** 10,841 (original dataset)
- **Features:** 13 columns

### Dataset Attributes

| Column | Description |
|---|---|
| App | Application name |
| Category | App category |
| Rating | Average user rating |
| Reviews | Number of user reviews |
| Size | Application size |
| Installs | Number of installations |
| Type | Free or Paid |
| Price | Application price |
| Content Rating | Target audience |
| Genres | Application genre |
| Last Updated | Last update date |
| Current Ver | Current app version |
| Android Ver | Minimum Android version |

## Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical computations and array operations
- **Pandas** – Data manipulation and preprocessing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Plotly** – Interactive visualizations
- **Scikit-learn** – Categorical encoding and numerical scaling
- **Jupyter Notebook** – Development environment

## Project Workflow

### 1. Dataset Collection
Collected the Google Play Store Apps dataset from Kaggle in CSV format.

### 2. Python and NumPy
Performed array creation, indexing, slicing, arithmetic operations, and statistical calculations.

### 3. Pandas Operations
Loaded the dataset into a DataFrame and explored records, dimensions, data types, summary statistics, missing values, and duplicates.

### 4. Data Cleaning and Preprocessing
- Handled missing values.
- Removed duplicate and malformed records.
- Converted columns into appropriate data types.
- Detected outliers using the Interquartile Range (IQR) method.
- Compared the dataset before and after cleaning.

### 5. Exploratory Data Analysis (EDA)
Analyzed numerical and categorical variables, app categories, ratings, installations, pricing, and correlations.

### 6. Data Visualization
Created the following visualizations using Matplotlib and Seaborn:
- Histogram
- Bar Chart
- Line Chart
- Scatter Plot
- Box Plot
- Correlation Heatmap

### 7. Interactive Visualization
Created interactive charts using Plotly:
- Interactive Histogram
- Interactive Scatter Plot
- Interactive Bar Chart

### 8. Feature Engineering
Created meaningful features such as:
- Popularity Level
- Reviews per Install
- App Size Category
- Update Year
- Update Month

Also applied Label Encoding and Standard Scaling.

### 9. Analysis and Conclusion
Summarized the findings, identified patterns and relationships, and discussed recommendations and dataset limitations.

## Project Structure

```text
google-play-store-data-analysis/
│
├── Google_Play_Store_Data_Analysis_Practical.ipynb
├── googleplaystore (1).csv
├── cleaned_googleplaystore.csv
├── feature_engineered_googleplaystore.csv
├── encoded_googleplaystore.csv
├── scaled_googleplaystore.csv
└── README.md
```

## Key Learning Outcomes

- Practical understanding of Python for data analysis.
- Experience with NumPy arrays and Pandas DataFrames.
- Data cleaning and preprocessing techniques.
- Exploratory and statistical data analysis.
- Static and interactive data visualization.
- Feature engineering and data transformation.
- Drawing insights from real-world datasets.

## Limitations

- The dataset represents a historical snapshot of Google Play Store applications.
- Installation counts are rounded or represented in ranges.
- Missing ratings require statistical imputation.
- User demographics and individual review sentiments are not included.
- Correlation does not necessarily imply causation.

## Conclusion

This project demonstrates an end-to-end data analysis workflow using the Google Play Store Apps dataset. It provides practical experience in data manipulation, preprocessing, statistical analysis, visualization, and feature engineering using Python.
