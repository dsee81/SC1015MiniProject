# CO2 Emissions Exploration and Prediction. 
## **About** ##

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on analysing the predictor variables for the CO2 Emissions of vehicles and suggesting environmentally friendlier suggestions based on these insights. Our Jupyter notebook consists of the following:
1. Introduction to the Dataset and Problem
2. Data Cleaning
3. Exploratory Data Analysis
4. Regression Techniques (Multilinear Regression, Ridge Regression and Lasso Regression)

## **Contributors** ##
1. @dsee81 - Exploratory Data Analysis
2. @CleonChua - Regression Techniques
3. @yitingeee - Data Cleaning + Preparing Data

## **Problem Definition** ##
1. What are the variables from our dataset that contribute most significantly to the CO2 Emissions of a vehicle?
2. What is the best regression model we can use to predict the most significant variable affecting CO2 Emissions? 

## **Models used** ##
1. Multilinear Regression - Served as a baseline for our predictive modeling
2. Ridge Regression - Used to address some of the limitations of linear regression, particularly its vulnerability to multicollinearity
3. Lasso Regression - Applied to enhance model simplicity and interpretability by reducing the number of variables with non-zero coefficients

## **Conclusion** ##

From the 3 models we have used, we decided that Lasso Regression is the best at predicting carbon emissions. Multilinear regression is unable to perform in-depth feature selection. Comparing to Ridge Regression, Lasso Regression can perform automatic feature selection by shrinking non-important variables to 0. Lasso Regression also helps us to better identify the most significant variables in impacting CO2 Emissions, while having a similar performance to Ridge Regression in terms of R^2 and MSE. Therefore we chose Lasso Regression as the best regression model.

We have found that fuel consumption is the most significant factor causing carbon emissions. This may be because our dataset is from Canada, and cars in Canada spend statistically long times in traffic jams which consumes more fuel. To allow for our insights to be more applicable to Singapore, we also considered other important variables such as Fuel Type, especially cars using Ethanol, that lead to higher carbon emissions.

We recommend the government to provide COE subsidies to cars that consume less fuel, such as electric cars, to encourage car owners to switch to environmentally friendly cars. Discounts can also be given for cleaner fuels such as natural gas over cars that can only use Ethanol. This brings Singapore one step closer to preserving a sustainable environment. 

## **Knowledge gained** ##
- Handling a large dataset (7000+)
- One-hot encoding
- Ridge and Lasso regression
- Efficient and effective data visualisation
- Collaborating on Github
- Kurtosis and Skewness measures
- Multicollinearity tests- chi-square testing, correlation comparisons


## **References** ##
- https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles
- https://business.yougov.com/content/47987-behind-the-wheels-car-ownership-in-singapore
- https://www.greenplan.gov.sg/
- https://medium.com/greenplan/greener-travels-ahead-3f6b5f63f125
- https://www.firestonecompleteautocare.com/blog/driving/how-to-reduce-fuel-consumption/
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.chi2_contingency.html
- https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c
