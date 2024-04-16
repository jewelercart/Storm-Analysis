# Storm-Analysis

# Analysis Steps

Data Loading and Preprocessing - The code loads hurricane data from the provided Excel file into a Pandas DataFrame, fills missing values with zeros, and calculates the average 'Big' value for each year.
Categorization of Hurricanesm- A function is defined to categorize hurricanes based on wind speed. The categorization is applied to the DataFrame.
Visualization - The code filters data from 1950 onwards and plots the count of hurricanes for each category using Matplotlib.
Normalization - The columns 'Big', 'Temp', and 'Number' are normalized using Min-Max Scaling.
Visualization with Seaborn - Normalized data is plotted using Seaborn to visualize the trends in temperature, tornado frequency, and tornado magnitude over the years.
Correlation Analysis - The code calculates the correlation between temperature and tornado frequency/magnitude using Pearson correlation coefficient.
Jointplot Visualization - Seaborn's jointplot is used to visualize the relationship between temperature and tornado frequency/magnitude.
Linear Regression Modeling - Simple linear regression models are fitted to analyze the relationship between temperature and tornado frequency/magnitude.
Summary Visualization - Model summaries are converted to HTML and plotted as images for better visualization.
# Results
The analysis reveals correlations between temperature and tornado frequency/magnitude.
Linear regression models indicate the impact of temperature on tornado frequency and magnitude.
# Contributors
Fredrick Jones 
Initial analysis and code implementation.
