# Problem Statement 
The subject matter of this dataset contains the stock prices of the 10 popular companies ( Apple, Amazon, Netflix, Microsoft, Google, Facebook, Tesla, Walmart, Uber and Zoom). This project specifically uses Apple's stock 
## Dataset

The dataset used is the Historical Stock Price of (FAANG + 5) companies (https://www.kaggle.com/suddharshan/historical-stock-price-of-10-popular-companies) from Kaggle.
<br>
The dataset has data regarding following features:
<br>
- The date - "Date"
<br>
- The opening price of the stock - "Open"
<br>
- The high price of that day - "High"
<br>
- The low price of that day - "Low"
<br>
- The closed price of that day - "Close"
<br>
- The amount of stocks traded during that day - "Volume"
<br>
- The stock's closing price that has been amended to include any distributions/corporate actions that occurs before next days open - "Adj[usted] Close"
<br>
- Time period - 2015 to 2021 (day level)


## Models Used

### 1. Linear regression
 Linear Regression is the supervised Machine Learning model in which the model finds the best fit linear line between the independent and dependent variable i.e it finds the linear relationship between the dependent and independent variable.
 <br>
 This regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression.
<br>
The typical equation of a line is y = mx + a, where m is the slope, x is independent variable and y is dependent variable that we are interested in predicting

### 2. Support Vector Regression
Support Vector Machine can also be used as a regression method, maintaining all the main features that characterize the algorithm (maximal margin). The Support Vector Regression (SVR) uses the same principles as the SVM for classification, with only a few minor differences. First of all, because output is a real number it becomes very difficult to predict the information at hand, which has infinite possibilities
<br>
Assuming that the equation of the hyperplane is as follows:

Y = wx+b (equation of hyperplane)
Then the equations of decision boundary become:

wx+b= +a

wx+b= -a

Thus, any hyperplane that satisfies our SVR should satisfy:

-a < Y- wx+b < +a 

Our main aim here is to decide a decision boundary at ‘a’ distance from the original hyperplane such that data points closest to the hyperplane or the support vectors are within that boundary line.

## Future Work
Testing with more regression algorithms and using stocks data of other companies to deduce their dependence. 
<br>
Also consider using date-time data to do a time-series analysis.
