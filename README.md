Add files via upload
Task: Identifying Key Correlates of Gross Earnings
1. Data Cleaning:

Handling Missing Values: Used KNNImputer to fill missing values without disturbing correlations.
Removing Duplicates: Identified and removed duplicates to ensure data accuracy.

2. Visualizations:

Scatter and Regression Plots: Assessed the relationship between budget and gross revenue visually.

3. Pearson Correlation Analysis:

Dependency Analysis: Computed Pearson correlation coefficients for numerical columns to quantify their relationship with gross revenue.
Heatmap Visualization: Created a heatmap for easier visualization of the correlation matrix.

4. Encoding Categorical Values:

Conversion to Numerical Form: Converted categorical values into numerical codes to include them in the correlation analysis.
Extended Analysis: Recalculated and visualized correlations with categorical variables included.

5. Comprehensive Correlation Matrix:

Correlation Calculation: Calculated correlations for all variable pairs and identified those with a coefficient greater than 0.5.

6. Conclusion:

Key Findings: Budget and votes have the highest correlation with gross earnings (0.71 and 0.63, respectively), indicating their significant impact on revenue.
