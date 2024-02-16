# Walmart Sales Data Analysis and Visualization

## Project Overview
This project is a comprehensive data analysis and visualization exercise on Walmart's sales data. Our objective is to unravel the sales patterns, identify top-performing stores and departments, assess the impact of holidays on sales, and gauge the influence of external factors such as fuel prices, CPI, and unemployment rates on sales figures.

## Steps and Components

### Data Preparation and Cleaning:
- **Libraries**: Importing essential libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`.
- **Data Reading**: Loading various CSV files as dataframes to include training, testing, features, and store information.
- **Data Cleaning**: Checking for null values and performing an initial statistical analysis to understand the datasets' structure.

### Data Exploration:
- **Sales Data**: Diving into `train_df` to extract insights from weekly sales data, including holiday effects.
- **Statistical Summary**: Describing numerical columns for a preliminary grasp on data distribution.
- **Null Value Analysis**: Investigating missing entries, particularly in markdown columns and economic indicators.

### Data Merging:
- **Data Integration**: Combining features and store data on the 'Store' column for enriched analysis.
- **Date Conversion**: Transforming date strings into `datetime` objects and generating 'week' and 'year' columns for temporal analysis.

### Data Visualization:
- **Scatter Plots**: Exploring relationships between stores, departments, and weekly sales.
- **Line Plots**: Tracing weekly sales trends across different years.
- **Histograms**: Analyzing sales distribution and computing skewness and kurtosis.
- **Box Plots**: Comparing store sizes across different store types.
- **Bar Charts**: Illustrating average weekly sales per store and per department visually.

### Statistical Analysis:
- **Aggregation**: Grouping data by store and department to compute average weekly sales.
- **Performance Visualization**: Presenting sales performance through bar graphs and line plots.

### Advanced Insights:
- **Sales Distribution**: Examining sales data distributions and their statistical properties.
- **Correlation Heatmap**: Utilizing heatmaps to uncover the relationships between different features.

## Project Aim
The project leverages a variety of data visualization techniques to provide actionable insights into Walmart's sales operations. Through meticulous analysis, we aim to assist in strategic decision-making to optimize sales strategies and improve business outcomes.

