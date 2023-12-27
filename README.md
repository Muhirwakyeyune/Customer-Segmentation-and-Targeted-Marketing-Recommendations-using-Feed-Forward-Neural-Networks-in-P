# Customer Segmentation and Targeted Marketing Recommendations using Feed-Forward Neural Networks

This project focuses on customer segmentation and targeted marketing recommendations using a Feed-Forward Neural Network (FFNN) implemented in PyTorch. The FFNN is trained on the Iris dataset to classify different species based on their features. The project demonstrates the steps to import necessary libraries, load and preprocess the dataset, define the neural network architecture, train the model using minibatch gradient descent, and evaluate the network's accuracy.

## Usage

### Step 1: Import Necessary Libraries

```python
# step 1 import necessary libraries
import torch
import torch.nn as nn
import torch.optim as optim
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split

### step 2 load iris datasets and split into test and train sets
iris = load_iris()
# split the data
X_train, X_test, y_train, y_test = train_test_split(iris.data, iris.target, test_size=0.2, random_state=42)



