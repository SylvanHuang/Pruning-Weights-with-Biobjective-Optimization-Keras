# Pruning-Weights-with-Biobjective-Optimization-Methods-in-Keras
Overparameterization and overfitting are common concerns when designing and training deep neural networks. Network pruning is an effective strategy used to reduce or limit the network complexity, but often suffers from time and computational intensive procedures to identify the most important connections and best performing hyperparameters. We suggest a pruning strategy which is completely integrated in the training process and which requires only marginal extra computational cost. The method relies on unstructured weight pruning which is re-interpreted in a multiobjective learning approach. A batchwise Pruning strategy is selected to be compared using different optimization methods, of which one is a multiobjective optimization algorithm. As it takes over the choice of the weighting of the objective functions, it has a great advantage in terms of reducing the time consuming hyperparameter search each neural network training suffers from. Without any a priori training, post training, or parameter fine tuning we achieve highly reductions of the dense layers of two commonly used convolution neural networks (CNNs) resulting in only a marginal loss of performance. Our results empirically demonstrate that dense layers are overparam<img src="http://some_place.com/image.png" />eterized as with reducing up to 98% of its edges they provide almost the same results. We contradict the theory that retraining after pruning neural networks is of great importance and opens new insights into the usage of multiobjective optimization techniques in machine learning algorithms in a Keras framework.  

![alt text](https://github.com/malena1906/Pruning-Algorithms-with-SMGD-in-Keras/blob/master/Figure1TowardsEfficientNetworkArchitectures.png?raw=true)



The Stochastic Multi-Gradient Descent Algorithm implementation in Python3 is for usage with Keras and adopted from paper:
S. Liu and L. N. Vicente: "The stochastic multi-gradient algorithm for multi-objective optimization and its application to supervised machine learning". 

It is combined with weight pruning strategies to reduce network complexity and inference time and extended to Keras optimizers Adam and RMSProp.
Experimental Results for the combination of pruning and biobjective training can be found in: 
Reiners, M., Klamroth, K., Stiglmayr, M., 2020, Efficient and Sparse Neural Networks by Pruning Weights in a Multiobjective Learning Approach, ARXIV CODE HERE

<p align="center">
  <img src="https://github.com/malena1906/Pruning-Algorithms-with-SMGD-in-Keras/blob/master/pareto-front-with-knee.png?raw=true" />
</p>
