# Walmart Sales Over Time Project

This project aims to analyze a comprehensive dataset containing weekly sales data from different stores. The analysis is conducted using the Python programming language and various data science libraries.

## Objectives

The main objective of this project is to evaluate store performance, understand sales trends, and examine customer behaviors by analyzing weekly sales data. The project has the following specific objectives:

1. Data Preparation: Address missing data, remove unnecessary columns, and preprocess the data through data preprocessing steps.

2. Store Performance Analysis: Compare average weekly sales among stores to assess store performance.

3. Overall Sales Analysis: Evaluate overall sales performance by determining total weekly sales for all stores.

4. Weekly Sales Variability: Examine sales variability by calculating the standard deviation of weekly sales.

5. Holiday Weeks: Identify holiday weeks in the dataset and analyze sales during holiday periods.

6. Relationship with Weather and Economic Indicators: Investigate the correlation between weekly sales and weather conditions, fuel prices, and Consumer Price Index (CPI).

7. Customer Segmentation: Utilize data analytics methods to classify customers and understand customer behaviors.

8. Interpretation and Recommendations: Interpret the results obtained at the end of the project and provide recommendations to improve sales strategies and performance for the stores.

## Requirements

To run this project, make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- plotly

The project file structure is as follows:

```
Walmart-Sales-Over-Time_Project/
    ├── data/
    │   └── walmart_sales_data.csv
    ├── notebooks/
    │   └── walmart_sales_analysis.ipynb
    ├── utils/
    │   └── data_preprocessing.py
    └── README.md
```

## Dataset

The project is conducted on a dataset containing weekly sales data. The dataset has the following features:

- Store: Store number.
- Date: Date of the sale.
- Weekly_Sales: Weekly sales amount.
- Holiday_Week: A column indicating whether the week is a holiday week or not.
- Temperature: Weekly average temperature value.
- Fuel_Price: Weekly average fuel price.
- CPI: Consumer Price Index.
- ... (Other features)

The dataset has been preprocessed and missing data has been handled.

## Running the Project

1. Download the project files and place them in the working directory.
2. Open the `walmart_sales_analysis.ipynb` Jupyter Notebook.
3. Run the notebook step by step to perform the analysis and explore the results.

## Project Results

The project results and analyses provide valuable insights into optimizing sales strategies and understanding customer behavior. Leveraging the results of customer segmentation, businesses can tailor marketing strategies to different customer segments, leading to increased customer satisfaction and improved sales performance. Moreover, the analysis results identify long-term sales patterns and potential growth opportunities, guiding inventory management and resource allocation.

The project showcases the significance of a data-driven approach in making business decisions. Therefore, regularly updating the project results and incorporating new data can continuously improve business performance.
