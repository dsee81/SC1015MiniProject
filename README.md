# CO2 Emissions Exploration and Prediction. 
**About**

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on CO2 Emissions of vehicles. Our notebook consists of the following:
1. Introduction to the Dataset and Problem
2. Data Cleaning
3. Exploratory Data Analysis
4. Regression Techniques (Multilinear Regression, Ridge Regression and Lasso Regression)

**Contributors**
1. @Dsee81 - Exploratory Data Analysis
2. @CleonChua - Regression Techniques
3. @yitingeee - Data Cleaning + Preparing Data for Regression.

**Problem Definition**
1. Are we able to predict how much CO2 a vehicle would emit based on its specifications?
2. Which regression model would be the best to predict this?

**Models used**
1. Multilinear Regression
2. Ridge Regression
3. Lasso Regression

**Conclusion**

From the 3 models we have used, we decided that Lasso regression is the best at predicting carbon emissions for our dataset. Multilinear regression is unable to perform in depth feature selection. Comparing Ridge and Lasso regression, Lasso Regression can perform automatic feature selection by shrinking non-important variables to 0. Lasso Regression also helps us to better identify the most significant variables in impacting CO2 Emissions, having a similar performance to Ridge Regression in terms of R^2 and MSE, therefore we chose Lasso Regression.

We have found that fuel consumption is the most significant factor causing carbon emissions. This is because cars in Canada spend a long time in traffic jams, leading to idling cars, which consumes more fuel. Hence,we also found second most significant variable, ethanol, to allow the data to be more applicable to Singapore. 

We recommend the government to provide COE subsidies to cars that consume less fuel, such as electric cars, to encourage car owners to switch to environmentally friendly cars. Discounts can also be given for cleaner fuels such as natural gas. This brings Singapore one step closer to a sustainable environment. 

**Knowledge gained**
- Handling a large dataset (7000+)
- One-hot encoding
- Ridge and Lasso regression
- Chi-Square tests on Categorical Variables.
- Collaborating on Github
- Kurtosis and Skewness measures


**References**
- https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles
- https://business.yougov.com/content/47987-behind-the-wheels-car-ownership-in-singapore
- https://www.greenplan.gov.sg/
- https://medium.com/greenplan/greener-travels-ahead-3f6b5f63f125
- https://www.firestonecompleteautocare.com/blog/driving/how-to-reduce-fuel-consumption/
