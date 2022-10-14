<img src="crisp-dm-framework.jpeg">

## Ask the following questions to understand the business issue:
* What decision needs to be made?
* What information is needed to inform that decision?
* What type of analysis is needed to get the information needed to make that decision?

<img src="methodology-map.jpg">

## Linear regression for predictions

A scatterplot that shows the plots in a line and line is drawn on the plots.

Using the line, you can predict the later or future plots.

y = mx + b
the `y` is the variable on the y axis - target variable, or the reason for the model used
the `x` is the variable on the x axis - predictor variable, or the game changer

`m` = slope of line
`b` = y-interscept

Slope function    `SLOPE(data_y, data_x)`
Intercept function    `INTERCEPT(data_y, data_x)`
---

#### Validation of model

Stage One - Correlation
correlation function `CORREL(data_y, data_x)`

we can calculate the correlation between the target and predictor variable. 
This value is often referred to as `r`. 
The range of r is from -1 to +1. 
The closer r is to plus or minus 1

stage Two - Calculate r-squared

While a strong correlation is good, we really want to know how well the data fits our line. 
Fortunately, we can get a sense of how good the formula is at approximating the data by calculating the coefficient of determination, or r-squared. 

R-squared is a coefficient between 0 and 1. 
R-squared is interpreted as the percent of variance in observations that is explained by the model, or the explanatory power of the model. 

An R-squared value close to 1 would mean that nearly all variance in the target variable is explained by the model. 
An R-squared value close to 0 would mean that nearly none of the variance in the target variable is explained by the model.

