# Customer Segmentation and Targeted Marketing Recommendations using Feed-Forward Neural Networks

This project focuses on customer segmentation and targeted marketing recommendations using a Feed-Forward Neural Network (FFNN) implemented in PyTorch. The FFNN is trained on the Iris dataset to classify different species based on their features. The project demonstrates the steps to import necessary libraries, load and preprocess the dataset, define the neural network architecture, train the model using minibatch gradient descent, and evaluate the network's accuracy.



## Introduction

Advancements in machine learning have enabled businesses to employ data-driven approaches for customer segmentation and targeted marketing. This project focuses on the application of a Feed-Forward Neural Network (FFNN) using PyTorch to classify different Iris species based on the Iris dataset. The primary goal is to understand the steps involved in customer segmentation using neural networks.

## Datasets

The Iris dataset, a well-known dataset in machine learning, is used for this project. It consists of features related to Iris flowers, such as sepal length, sepal width, petal length, and petal width. The dataset is divided into training and testing sets to evaluate the model's performance.

## Methods

1. **Neural Network Architecture:**
   - A Feed-Forward Neural Network with three fully connected layers is designed.
   - The architecture includes an input layer with 4 features, two hidden layers with 10 neurons each, and an output layer with 3 neurons corresponding to Iris species.

2. **Model Training:**
   - The model is trained using the Adam optimizer and CrossEntropyLoss criterion.
   - Mini-batch gradient descent is employed with a batch size of 32 and 1000 epochs.

## Results

The training process demonstrates a steady decrease in loss, indicating the FFNN is learning the underlying patterns in the Iris dataset. The final accuracy on the test set provides an evaluation metric, showcasing the model's ability to generalize.

## Conclusion

This project illustrates the application of FFNNs for customer segmentation, using the Iris dataset as a representative scenario. The implemented neural network successfully learns the features of different Iris species, highlighting the potential of such approaches in real-world customer segmentation and targeted marketing.

## Future Work

Future work could involve exploring more complex datasets and architectures, optimizing hyperparameters, and deploying the model for practical business use.

Feel free to use and modify this information for your specific use case or dataset.

*Note: The accuracy mentioned in the report is specific to the Iris dataset and may vary in different scenarios.*




