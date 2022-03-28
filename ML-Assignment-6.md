### Assignment 6

**1. What are the reasons for feature scaling?**
Ans: The reasons of feature scaling is it tries to bring the dataset into a particular range like 0 to 1. This also helps to converge to local minima quicker in gradient descent Algorithm.

**2. What is the difference between Feature Selection under Feature Engineering? Can you perform feature selection using regularization, if yes then how?**
Ans: Feature selection is nothing but taking important features for training the model rather than taking entire dataset. Yes, we can perform feature selection using Lasso(L1) regularization.

**3. Suppose you are working on a Machine Learning problem, your training accuracy is lower than the testing accuracy, what can be the reason for this?**
Ans: Its an Underfitting problem where it didn't tried to generate patters well on the data.

**4. You are training a machine learning model, your training and the testing accuracy are decreasing, what can be the reason for this?**
Ans: Maybe data provided to the model is not sufficient or lack of feature Engineering and feature scaling.

**5. What solutions you can provide for optimal bias-variance levels in a machine learning problem?**
Ans. firstly, Add more data followed by increasing the model complexity by using poly features or by decreasing the regularization term to hve balance between bias and variance
