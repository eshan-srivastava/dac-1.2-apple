# Historical Stock price of Apple
The subject matter of this dataset contains the stock prices of the 10 popular companies ( Apple, Amazon, Netflix, Microsoft, Google, Facebook, Tesla, Walmart, Uber and Zoom). This project specifically uses Apple's stock.
People dealing in stock market find it advantageous to have accurate prediction of how certain stocks are performing. These companies have extremely valuable stocks and thus its sinsight is valuable to people in the market.
## Dataset

- The date - "Date"

- The opening price of the stock - "Open"

- The high price of that day - "High"

- The low price of that day - "Low"

- The closed price of that day - "Close"

- The amount of stocks traded during that day - "Volume"

- The stock's closing price that has been amended to include any distributions/corporate actions that occurs before next days open - "Adj[usted] Close"

- Time period - 2015 to 2021 (day level)

**Target Variable** (in this case): High - highest price of the stack on a day.

**Open** {Mean: 61.2, Max: 181, Min: 22.5}

**High** {Mean: 61.9, Max: 182, Min: 22.9} 

**Close** {Mean: 61.3, Max: 180, Min: 22.6} 

**Low** {Mean: 60.6, Max: 179, Min: 22.4}

**Volume** (m = Million) {Mean: 138m, Max: 639m, Min: 41m} 

**Adj Close** {Mean: 59.8, Max: 180, Min: 21}

**Date**: from 2nd Jan 2015 to 29th Dec 2021

*However it is to be noted that in case of the nature of data, target variables and feature variables can be anything from : open, high, low, close, volume, adjusted close*

## Models Used

### 1. Linear regression
 Linear Regression is the supervised Machine Learning model in which the model finds the best fit linear line between the independent and dependent variable i.e it finds the linear relationship between the dependent and independent variable.
 This regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression.
The typical equation of a line is y = mx + a, where m is the slope, x is independent variable and y is dependent variable that we are interested in predicting

### 2. Support Vector Regression
Support Vector Machine can also be used as a regression method, maintaining all the main features that characterize the algorithm (maximal margin). The Support Vector Regression (SVR) uses the same principles as the SVM for classification, with only a few minor differences. First of all, because output is a real number it becomes very difficult to predict the information at hand, which has infinite possibilities
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
Also consider using date-time data to do a time-series analysis.
