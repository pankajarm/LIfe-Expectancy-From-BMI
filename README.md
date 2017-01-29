# LIfe-Expectancy-From-BMI

In this nano project, We'll use Simple linear regression (One Variable) to make prediction of People life expectancy from thier body mass index (BMI) from birth.

We are using SciKit Learn to Create Linear Regression Model

Read more about SciKit Learn LinearRegression Here
http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html

In this model we are using Simple Linear Regression equation
y = mX +b

In our example: y is Life Expectacny from data and X is BMI of people (These are given from data)

m is the slope between X and y, i.e. relationship factor and b is constant value ( These will be generated during model fit process)

Long Story short, They way it works (atleast in my understanding..), is SciKit Learn LinearRegression model will try to create a model of equation type y = mX + b from the given data which has BMI (X) and Life Expectancy (y), via fitting all values of X in relationship to y by finding slope m and by adding b (a constant value) to it.

Basically, by using SciKit Learn Linear Regression fit method, we are telling it to find correct relationhip between given Data of X (BMI) and y (Life Expectancy)

Hope it all make sense to you...


Read more about Body Mass Index and how it impacts people health in various ways, and ultimately life expectancy Here:
https://en.wikipedia.org/wiki/Body_mass_index

Data taken from https://www.gapminder.org/ showing life expectancy of people in different country in correlation to BMI
