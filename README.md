# Nested-Spheres
Simulation is an incredibly useful tool in data science. We can use simulation to evaluate how algorithms perform against ground truth, and how algorithms compare to one another.  In this project, I will be implementing and extending the nested spheres simulation study found in Elements of Statistical Learning page 339.

**The Simulation Study**

These are the steps I have followed in this project:

**Steps:**

1) Generate  a training data set of 2000 observations according to the description above. Label each of these training examples
according to the rule above.

2) Train a bagged estimator, a random forrest with max_features=1, a random forest with max_features=3, and an additional model of your choice (you can increase max features again, or you can explore a boosted estimator). Use 500 trees in your random forests and bagged estimator.

3) Generate a testing data set of 10,000 observations according to the description above. Label each of these training examples according to the rule above.

4) Use each model to predict on the testing data. Record the testing error rate (that is 1 - accuracy).

5) Repeat these steps 50 times. Plot the error rates as a box plot by model to complete the assignment.
