# Logistic-Regression-Model-from-scratch
Logistic Regression model is developed from scratch. During model training:

**Scenario 1:** Gradient is calculated as: <br>
np.dot(X.T, (sigmoid(X.W) - y)) / N

**Scenario 2:** Gradient is calculated by Central Difference Formula
![image](https://user-images.githubusercontent.com/52847288/117814269-b5780880-b281-11eb-9157-093cdce39e6b.png)

Their performance is compared with a sklearn model in terms of performace and wall time to train:

![image](https://user-images.githubusercontent.com/52847288/117815275-ee64ad00-b282-11eb-904c-9b101c0805a9.png)

