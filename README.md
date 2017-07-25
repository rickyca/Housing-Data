## Ames Housing Data

Let's predict 2010 sales (test data) using data from previous years.

The notebook performs some explarotary analysis, performs some regularization, finds the best Linear Regression model and does some hyper-parameter tuning. Fixed features were considered for this analysis. This means that features that can't be changed of a house were used for this model (for example lot size, lot shape or location)

The output of the first model is used by a second linear regression model in order to predict the difference in price using not fixed features. From a sales point of view, this could be updates or improvements done to the property in order to maximaze revenew.

This is a image of the overall model:

![alt text](https://raw.github.com/rickyca/Housing-Data/master/model.png)

Additionaly, I did some extra analysis of Abnormal sales, which is considered a 'rare class'. Slides are included in the repository
