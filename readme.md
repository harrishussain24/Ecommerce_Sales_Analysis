Sales Data Analysis

Overview

This project analyzes a sales dataset to explore trends, correlations, and insights related to product pricing, sales performance, and customer ratings. The analysis includes data cleaning, handling missing values, data visualization, and statistical analysis.

Dataset
The dataset used in this project is summer-products-with-rating-and- performance\_2020-08.csv. It contains various attributes related to product sales, including:
    - Retail Price
    - Selling Price
    - Units Sold
    - Product Color
    - Rating Count
    - Crawl Month
    - …
Dataset Source: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data

Dependencies

Ensure you have the following Python libraries installed: pip install numpy pandas matplotlib seaborn

Data Preprocessing

- Checked for missing values and handled them by filling with median or categorical placeholders.
- Converted crawl\_month column to datetime format.
- Removed outliers using the Interquartile Range (IQR) method.

Exploratory Data Analysis (EDA)

The analysis includes:

- Statistical Summary: Checked data types, unique values, and descriptive statistics.
- Data Cleaning: Handled missing values and transformed categorical features.
- Visualization:
- Retail price distribution and its impact on units sold.
- Correlation heatmap for numerical features.
- Top & worst-selling products based on colors.
- Price and discount analysis.
- Monthly sales trend.

Key Insights

- Products within a certain price range had significantly higher sales.
- Some product colors sold better than others.
- Strong correlation between five-star ratings and sales performance.
- Seasonal trends were observed in product sales.

Visualizations

The project uses matplotlib and seaborn to generate:

- Line charts for price vs. sales
- Bar charts for top and worst-performing products
- Scatter plots for sales trends
- Heatmaps for correlation matrices

How to Run the Project

1. Download the dataset and place it in your project folder.
1. Open the Jupyter Notebook (sales\_analysis.ipynb).
1. Run the cells sequentially to execute the analysis.
1. The output will include printed insights and displayed visualizations.

Future Improvements

- Implement machine learning models to predict future sales trends.
- Perform deeper sentiment analysis on product ratings.
- Expand the dataset to analyze long-term trends.

Author

Harris Hussain <harrishussain2408@gmail.com>

License

This project is open-source and available under the MIT License.
