# Machine Learning Algorithms from Scratch
Implemented the algorithm with gradient descents from scratch using numpy and pandas


Algorithm Included are,
1. Linear Regression-one feature
2. Multilinear regression-Vectorized
3. Multilinear regression-Closed form
4. Polynomial Regression
5. Logistic Regression
6. Naive Bayes
7. KNN Hard and Soft Parzen
8. PCA- to reduce the dimension of the input feature
9. SVC-Support Vector classifier
10. Neural Network with relu,sigmoid, tanh, leaky relu activations

# My Biggest Learning,
1. Normalize the data for linear models, if not the weights and bias will explode. it will also be helpful for the model to compare and contrast with the other input feature
2. Each and every alorithm has its own advantage and disadvantage, understand it more so that you will know why so models perform good while other not EG:linearly seperable and non linearly seperable
3. Every algorthim has assumption like Independent Identical Distributed(IID) , gaussian. if the assumption fails in the dataset, the algorithm will perfom poorly
4. Use validation set to select the right hyper parameters(these parameters changes from problem to problem) and you can balance between bias and variance. Make sure there is no data leakage
5. Gradients are important for the model to learn the right parameters with the perfect learning rate. If your learning rate is high, the gradient will diverge. If your learning rate is too less it take more epoches to converge
6. Normalization is important in Neural Network as it reduces the time and memory during the computation of the dot product during the
forward and back propagation which helps the model to converge faster and can achieve high accuracy in less epochs when compared with not normalized data.
