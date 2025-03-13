Exploratory Data Analysis (EDA) Report

1. Dataset Overview
Data Attributes
Numerical: `Unit price`, `Quantity`, `Tax 5%`, `Total`, `Gross income`, `Rating`
Categorical: `Branch`, `City`, `Customer type`, `Gender`, `Product line`, `Payment`
Time-based: `Date`, `Time`

2. Data Cleaning
- No missing values were found.
- Duplicates and outliers are removed.
- All numerical values were properly formatted.
- All categorical were formatted.

3. Exploratory Data Analysis (EDA)
3.1 Univariate Analysis

 Numerical Variables: Total, Quantity, and Gross income show a right-skewed distribution, indicating most transactions involve smaller amounts.

 Categorical Variables: Product line distribution shows some categories have significantly higher sales than others.

 Rating Distribution: Most ratings are concentrated around the mid-to-high range, suggesting general customer satisfaction.

3.2 Bivariate Analysis

 -Total is highly correlated with Quantity and Gross income, confirming that higher sales volumes result in higher revenues.

 -Rating has no strong correlation with spending patterns, suggesting factors beyond price influence customer satisfaction.

 -Branch and City comparisons reveal differences in sales performance across locations.
Pair Plot Analysis
- `Total` is highly correlated with `Quantity` and `Gross income`.
- `Rating` shows no strong correlation with monetary values.

Heatmap: Correlation Analysis
- `Total` and `Tax 5%` have a near-perfect correlation (0.99).
   So we remove tax as they are highly corelated.
- `Gross income` and `Total` are strongly correlated.
- `Unit price` does not impact `Rating` significantly.

Grouped Comparisons
- No major spending differences between genders.
- Sales vary across different `Product lines`.
- Regular customers spend slightly more than first-time buyers.



