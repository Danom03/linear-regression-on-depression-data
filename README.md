# linear-regression-on-depression-data
Applying linear regression on employment data downloaded from Kaggle and checking linear regression assumptions on it.

## Excel Contains
The Excel file, `employment data.xlsx`, contains the following sheets:
* **original_data**: It contains the original data downloaded from the Kaggle. The sheet has following columns: **id**,**Age**,**Sex**,**Employement Status**,**Sleep Quality**,**Stress Score**,**Anxiety Score**, **Depression Score**.
* **dummy_data**: It creates dummy variables for categorical columns.
* **regression(1)**: Baseline regression.
* **Significant_data**: Dropping the columns which does not add much information to the model.
* **regression(2)**: Regression applied on the data in `significant_data`.
* **heteroscedasticity(graph)**: Check for heteroscedasticity using graph.
* **heteroscedasticity(Spearman)**: Check for heteroscedasticity using Spearman Rank Correlation.
* **homoscedastic_data**: Removing heteroscedasticity from the data.
* **regression(3)**: Regression applied on `homoscedastic_data`.
* **Autocorrelation(Run Test)**: Check for autocorrelation using Run Test.
* **Mutlicollinearity**: Check for multicollinearity using the Variance Inflation Factor.

#Thank you for reading
