# banking-data-analysis
This project analyzes a bank marketing dataset to understand customer behavior and identify the key factors influencing term deposit subscriptions. The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), and data visualization to generate actionable business insights.

## Data Cleaning Summary <br>
- Checked dataset shape, structure, and data types.
- summary statistics using describe().
- Identified and removed duplicate records.
- Checked missing values across all columns.
- Standardized categorical values by converting text to lowercase.
- Replaced invalid values (999) with NaN.
- Replaced "unknown" values with NaN.
- Verified the cleaned dataset using info() and isna().sum().
  
## Key Insights <br>
- The dataset contains 41,188 records and 21 features.
- Duplicate records were removed to improve data quality.
- Invalid and unknown values were treated as missing values.
- Standardizing text values ensured consistent categorical data.
- The cleaned dataset is now ready for Exploratory Data Analysis (EDA) and visualization.
  
  **Data Visualization – Summary**
Performed data visualization using Matplotlib and Seaborn to explore customer behavior, feature distributions, correlations, and subscription trends. Various charts such as count plots, histograms, pair plots, and heatmaps were used to identify patterns and generate meaningful business insights.
