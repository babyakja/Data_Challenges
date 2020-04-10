# Collection of Data Challenge Questions and my responses

## Data Questions

_4.10.2020_

### Let's say we want to build a model to predict booking prices.

*1. Explain the difference between a linear regression versus a random forest regression.*
*2. Which one would likely perform better?*

> Response
1. Linear Regession fits a line (mX +b) to the by minimizing error between the residuals and actual value, in this case booking price
2. Given the nuance between location and seasonality, these would be identified easier in a random foreest regression. For example a 1000 sq ft home for rent in NY may be much higher than West Texas. Using square footage as a variable in a linear regression would not become as influental wthout the context of location.
