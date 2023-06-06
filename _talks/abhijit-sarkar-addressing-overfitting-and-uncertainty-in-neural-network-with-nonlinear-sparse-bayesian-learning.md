---
speakers:
  - Abhijit Sarkar
name: "Addressing Overfitting and Uncertainty in Neural Network with Nonlinear Sparse Bayesian learning"
categories:
  - Short Talks
hide: no
---
Deep neural networks suffer from two significant limitations in supervised learning tasks. 
First, their large number of weight parameters make them prone to overfitting. Second, the inability to comprehensively account for uncertainty in the training data,  can result in  overconfident predictions. While regularization schemes like early stopping, weight decay, and  dropout have been proposed to address the overfitting issue, they fail to addres the uncertainty 
quantification problem. Conversely, Bayesian neural networks (BNNs) introduce uncertainties in the network's  weights to address the uncertainty issue, but overfitting remains a significant challenge. 

To address both these problems simultaneously, the current study proposes a sparse Bayesian neural network (SBNN). The proposed algorithm aims to address the practical and computational issues  associated with BNNs by incorporating a sparsity-inducing prior based on the automatic relevance determination (ARD) concept.  While the use of a data-informed prior increases the level of hierarchy in the Bayesian analysis,  it is computationally manageable within the efficient semi-analytical framework of NSBL. The SBNN algorithm  identifies the optimal sparse neural network by removing redundant weight parameters, resulting  in a tractable treatment for overfitting through an evidence optimization algorithm. To demonstrate  the benefits of the SBNN algorithm, the study presents an illustrative regression problem and  compares the results with the  standard Bayesian neural network (BNN)  and the hierarchical Bayesian formulation of the BNN.

