# DeepLearning_Project

### This project contains two deep learning models with two different approaches to address the same problem, which is to categorize a given review under four categories.
* satisfied considerable comment
* satisfied neutral comment
* unsatisfied considerable comment
* unsatisfied neutral comment

Approaches
1. Supervices Learning with Functional Neural Network
2. Unsuperviced Learning with Autoencoders

### Model architecture of the Superviced Learning model is as follows,
* 1 Input Layer
* 1 Lambda Layer
* 1 Dropout Layer
* 1 Dense Layer
* Optimizer - adam
* Loss function - sparse categorical crossentropy

### Model architecture of the Unsupervised Learning model is as follows,
* Input Layer
* Dense Layer with ReLU
* Dense Layer with Softmax
* Optimizer - Adam
* Loss Function - mean square error
