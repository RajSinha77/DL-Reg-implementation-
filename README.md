# DL-Reg-implementation-
DL-Reg  vs L2 Reg  implementation on several state-of-the-art deep network architectures, such as ResNet-152, densenet, etc., and accuracy comparison 

Regularization is crucial in deep learning to prevent overfitting deep neural networks. This topic explains the novel deep learning regularization method, DL-Reg, designed to force the network to behave as linearly as feasible explicitly and thus limit the extent of nonlinearity. The idea involves introducing a linear constraint to the neural network's objective function, which penalizes the deviation from linearity and represents the error of a linear mapping from inputs to outputs. DL-Reg gently enforces this linear behavior by applying the constraint with a regularization factor while still capturing complex patterns, thereby balancing model simplicity and expressiveness, which inherently addresses the overfitting issue. 
This study also aims to experiment with DL-Reg and evaluate them on benchmark datasets, including MNIST and CIFAR-10, etc, and compare it with common regularization techniques like Dropout, Elastic Net, L1, and L2 regularization to verify why DL-Reg stands out among the others and whether its superiority as an improvement over others techniques can be counted as a valuable addition to the toolkit of regularisation techniques in deep leaning.  
The outcomes of the two experiments indicate the following: 
1) The suggested method provides superior improvement over current regularization techniques 
2) DL-Reg improves the performance of deep networks by optimizing feature spaces, and it is most useful for small-sized training datasets.




" Page under construction "
