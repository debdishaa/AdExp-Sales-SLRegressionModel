# AdExp-Sales-SLRegressionModel

## Project: Advertising Expenditure and Sales Prediction

### Project Description
This project aims to build a predictive model to analyze the relationship between a company's advertising expenditures across various media channels and the resulting sales figures. The dataset includes the following columns:

- **TV**: The amount spent on TV advertising.
- **Radio**: The amount spent on radio advertising.
- **Newspaper**: The amount spent on newspaper advertising.
- **Sales**: The corresponting sales amount.

### Objective
The goal is to build a simple linear regression model using the advertising medium with the highest coefficient, indicating the strongest relationship with sales. This will help us understand the impact of that specific advertising medium in isolation.

### Approaches
To accomplish this, I will use two different approaches:

#### 1. Statsmodels
Statsmodels provides a detailed statistical summary and insights into the linear regression model.

##### Pros:
- Offers comprehensive statistical tests and results.
- Provides a detailed summary of model parameters, including p-values and confidence intervals.
- Useful for in-depth statistical analysis and understanding model behavior.

##### Cons:
- Slightly more complex to implement compared to scikit-learn.
- May require additional steps for preprocessing and validation. (e.g adding constant)

#### 2. Scikit-learn
Scikit-learn will be used to implement the linear regression model for its simplicity and efficiency in predictive analytics.

##### Pros:
- Easy to use and integrate with other machine learning libraries.
- Efficient for large datasets and complex workflows.
- Provides various utilities for model validation and tuning.

##### Cons:
- Limited in providing detailed statistical summaries compared to Statsmodels.
- Focuses more on predictive performance rather than statistical inference.

### Note:
By leveraging both Statsmodels and Scikit-learn, the objective is to determine the effectiveness of each advertising medium and to develop a model that can accurately predict sales based on advertising spend. 

