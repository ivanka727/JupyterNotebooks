# UCLA_CSX_450_2_2018_W_Project-3

# The domain of the problem
This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It was obtained from the StatLib archive (http://lib.stat.cmu.edu/datasets/boston), and has been used extensively throughout the literature to benchmark algorithms. The Dataset consists of price of houses in various places in Boston.Alongside with price, the dataset also provide information such as Crime (CRIM), areas of non-retail business in the town (INDUS), the age of people who own the house (AGE), and there are many other attributes that available as well. 

# Problem statement
We'll use the supervised learning to develop a regression model to predict the house median price. 

# Dataset Description
The dataset has 506 instances and 14 attributes.The medv is the target data. 
 1. CRIM     per capita crime rate by town
 2. ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
 3. INDUS    proportion of non-retail business acres per town
 4. CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
 5. NOX      nitric oxides concentration (parts per 10 million)
 6. RM       average number of rooms per dwelling
 7. AGE      proportion of owner-occupied units built prior to 1940
 8. DIS      weighted distances to five Boston employment centres
 9. RAD      index of accessibility to radial highways
 10. TAX      full-value property-tax rate per $10,000
 11. PTRATIO  pupil-teacher ratio by town
 12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
 13. LSTAT    % lower status of the population
 14. MEDV     Median value of owner-occupied homes in $1000's
 
![my image](https://github.com/lssnadia/UCLA_CSX_450_2_2018_W_Project-3/blob/master/Screen%20Shot%202018-02-15%20at%2011.08.02%20PM.png)

# A proposed solution
A solution could be develop a linear regression model.

# A benchmark model
A good native benchmark could be the mean or median of the house values.

# A performance Metric
we will be calculating the coefficient of determination, R2, to quantify our model’s performance. 
