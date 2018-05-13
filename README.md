# Artificial Neural Networks

In this repository, you can find related documents and my solutions of assignments about Prof. Dr. Ethem Alpaydin's Artificial Neural Networks course at Bogazici University. 

I would like to thank Burak Suyunu (@suyunu) for all help in these assignments.

### Assignment-I: Parametric Classification
* Estimate class priors, means and variances using the training data.
* Plot *training data*, estimated likelihoods and posteriors together on the same plot. Use different symbols for different classes. 
* Use your estimated discriminants to classify the test data and report the confusion matrix on the *test data*.

### Assignment-II: Linear Regression
* Inputs are 16x16 binary images and there are 10 classes. 
* You will implement linear logistic regression. 
* Show how training and test misclassifications change as training proceeds and report the final confusion matrices on training and test data.

### Reinforcement_Learning.ipynb
* We have a 8x8 grid world with a robot that can move in one of the four main directions (N,W,E,S). Initial state is (2,2) and the goal is at (7,6). Reward at reaching the goal is 100 and \gamma=0.9. Rewards and next states are deterministic.
* Implement Q learning
* Assume that the next state is nondeterministic where with probability 0.5 we move in the intended direction and with probability 0.25 each, we move in the two orthogonal directions. E.g., when we want to go N, with prob 0.5 we do go N, with prob 0.25 we move E and with prob 0.25, we move W. The reward at reaching the goal is still always 100 (as in the deterministic case). Implement sarsa, print the 8x8 matrix with the Q values for the 4 actions (show the best action in bold).
