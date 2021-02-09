## Statistical Analysis / Regression

#### 1. Distinguish between categorical and continuous independent variables

* The idea was to split the dataset into two sub-datasets one of which consists of the continuous variables and the other of the categorical.

#### 2. Found the top continuous regressors based on the correlation coefficient

* Performed some tests to find which features should be selected

#### 3. Found the top categorical regressors

* At this point columns of dummy variables were created in order to be able to perform linear model regression analysis.

* After having found the highest ones were able to reduce the number of categorical features.

#### 4. Last step

* Merged both the top continuous and the top categorical features into one single dataframe along with the sale prices.

* Performed a final test where the rsquared value could be obtained for the whole feature list.

