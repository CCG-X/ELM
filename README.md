# Extreme Learning Machine(ELM)
In ELM, the input weights (linking the input layer nodes to the hidden layer nodes) and biases of hidden layer nodes are randomly assigned, then the output weights (linking the hidden layer nodes to the output layer nodes) are analytically determined by using the Moore-Penrose (MP) generalized inverse.

Dataset description

 The given training set contains 168 CPUs with 6 features each: Cache memory size, minimum and maximum number of I/O channels, machine cycle time, and minimum and maximum main memory. The regression task is to use related factors to evaluate the CPU performance.
 
 Case study
 
The model is established to predict the performance scores for the left 41 CPUs. In this experiment, the given training dataset has been split into two separate datasets using random cross validation method. To be specific, 80% of the training samples are used to train the model to obtain the optimum weight parameters and the left 20% samples were used as testing samples to examine the generalization performance of the established model. 


Lastest Version
