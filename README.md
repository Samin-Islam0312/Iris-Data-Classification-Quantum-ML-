# Iris-Data-Classification-Quantum-ML
Iris dataset classification is a quintessential task for learning the basics of Machine Learning. In this repository, Quatum circuit has been implemented, and 4 features of the dataset have been represented in 4 qubits to do this machine learning task. 

![image](https://user-images.githubusercontent.com/69072084/197596295-d88b93b6-b1dd-478d-9dbc-3c2f735570fa.png)

# Dataset
For this project, the most well-known open source dataset which is used for machine learning tasks. It contains information about three iris species, each flower's characteristics of 50 samples each. One flower species can be linearly divided into the other two, however the other two cannot be linearly divided into one another. 100 samples have been taken for training and testing the quantum machine learning model. 4 features have been represnted as 4 qubits{q0, q1, q2, q3}
Dataset has been split into 67/33.

# Processing
Variational circuit is used for training the quantum model. Stochastic gradient descent is required for minimizing loss. 

# Result 
The model has been run to 20 epoch, and at the loss - 0.21, accuracy - 84%

![image](https://user-images.githubusercontent.com/69072084/197598713-ee34c86f-66c1-40c8-bce7-9710cc334ef0.png)
