# Logistic-Regression-Model-from-scratch
Logistic Regression model is developed from scratch. During model training:

**Scenario 1:** Gradient is calculated as:
np.dot(X.T, (sigmoid(X.W) - y)) / N

**Scenario 2:** Gradient is calculated by Central Difference Formula
![image](https://user-images.githubusercontent.com/52847288/117814269-b5780880-b281-11eb-9157-093cdce39e6b.png)

Their perfiormance is compared with a sklearn model in terms of performace and wall time to train.
