# Salary Prediction Project(Python)

The purpose of this project is to use data transformation and machine learning to create a model that will predict a salary when given years of experience, job type, college degree, college major, industry, and miles from a metropolis.


# Methodology

 - Data Wrangling - `Removed duplicates and dropped misssing or null values in the dataset.`
 - Exploratory Data Analysis - `Analyzed the data and summarized the main characteristics.`
 - Data Visualization - `Used boxplot, distribution plot, scatter plot, violin plot, residual plot and regression plot to visualize the data and it's characteristics.`
 - Machine Learning Algorithms Used - `Linear Regression, Polynomial Transformation, Ridge Regression and Random Forest`
 - Evaluation Metrics Used - `Mean Squared Error(MSE) and R-squared`


# Technologies/Libraries Used
``` javascript
 - Python 3
 - Jupyter
 - Pandas
 - Numpy
 - Seaborn
 - Matplotlib
 - Scikit-Learn
 - Scipy
 ```

# Datasets available

The data for this model is fairly simplified as it has very few missing areas. The raw data consists of a training dataset with the features - jobType, degree, major, industry, yearsExperience and milesFromMetropolis and their corresponding salaries. Twenty percent of this training dataset was split into a test dataset with corresponding salaries.

There is also a testing dataset that does not have any salary information available and was used as a substitute for real-world data and used the model to predict it's values/salaries. 

## Information Used to Predict Salaries

-   **Years Experience:**  How many years of experience
-   **Job Type:**  The position held (CEO, CFO, CTO, Vice President, Manager, Janitor, and senior or junior position)
-   **College Degree:**  Doctoral, Masters, Bachelors, High School, or None
-   **College Major:**  Biology, Business, Chemistry, Computer Science, Engineering, Literature, Math, Physics, or None
-   **Industry:**  Auto, Education, Finance, Health, Oil, Service, or Web
-   **Miles From Metropolis:**  How many miles away from a major city


# Summary

*Applying second order polynomial transformation to the features led to the most accurate predictions with the least error when using a linear regression model. The result was a **mean squared error of 354** with a **76% accuracy rate**.<br>
This model can be used as a guide when determining salaries since it leads to reasonable predictions when given information on years of experience, miles from metropolis, job type, industry, and college degree and major.*


<!--stackedit_data:
eyJoaXN0b3J5IjpbNjQyMTcxNTIwLDE0NTUyNzg1NDEsMjEzNT
A2NjIxNywxMzA0MDczNjI1LDc0ODUzNzA4MSwtMTA5MzMwNzY5
OSwxNjczNjEwMTYzXX0=
-->