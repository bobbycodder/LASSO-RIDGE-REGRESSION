# LASSO-RIDGE-REGRESSION
In this Project, I have done implementation of different regularization techniques.

I've used Python's famous libraries like [Pandas](https://pandas.pydata.org/), [Numpy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [Sklearn](https://scikit-learn.org/), etc. for analysis and model development.

I've used the Boston house prediction dataset. This [dataset](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Dataset.txt) is present in the datasets module of sklearn (scikit-learn) library.

You can use **[Jupyter Notebook](https://jupyter.org/)** or **[Google Colab](https://colab.research.google.com/)** for Coding!


<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS0vps-Ck_HyS2HAG4hi93JKL6ygFhXFwvZCQ&usqp=CAU" width="400" height="200">

## Description:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


# What is Regularization

In regression analysis, the features are estimated using coefficients while modelling. 

Also, if the estimates can be restricted, or shrinked or regularized towards zero, then the impact of insignificant features might be reduced and would prevent models from high variance with a stable fit. 

***Regularization is the most used technique to penalize complex models in machine learning, it is deployed for reducing overfitting (or, contracting generalization errors) by putting network weights small. Also, it enhances the performance of models for new inputs.***

# Penalty Terms
 
Through biasing data points towards specific values such as very small values to zero, Regularization achieves this biasing by adding a tuning parameter to strengthen those data points. Such as:

* **L1 regularization:** It adds an L1 penalty that is equal to the absolute value of the magnitude of coefficient, or simply restricting the size of coefficients. For example, Lasso regression implements this method. 

* **L2 Regularization:** It adds an L2 penalty which is equal to the square of the magnitude of coefficients. For example, Ridge regression and SVM implement this method.


<img src="https://i2.wp.com/ucanalytics.com/blogs/wp-content/uploads/2018/04/Graph-0-Data-for-Regression-with-Regularization.jpg" width="400" height="200">

# Conclusion

From the above analysis we can reach the following conclusion about different regularization methods: 
 

  * **Regularization is used to reduce the dependence on any particular independent variable by adding the penalty term to the Loss function. This term prevents the coefficients         of the independent variables to take extreme values.** 
 
  * **Ridge Regression adds L2 regularization penalty term to loss function. This term reduces the coefficients but does not make them 0 and thus doesn’t eliminate any independent       variable completely. It can be used to measure the impact of the different independent variables.**
 
   * **Lasso Regression adds L1 regularization penalty term to loss function. This term reduces the coefficients as well as makes them 0 thus effectively eliminate the                    corresponding independent variable completely. It can be used for feature selection etc.** 
 

