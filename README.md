# -Neural_Network_Charity_Analysis

# Overview

The purpose of the analysis was to classify the success of charitable donations. This was accomplished using deep learning neural networks with the TensorFlow platform

# Results

# Data Preprocessing
The Column "IS_SUCCESSFUL" is the target variable for the deep learning neural network.
The EIN and NAME columns were removed from the input data as they were not useful for the model.
Feature columns for the deep learning neural network include "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT".


# Compiling, Training, and Evaluating the Model

The analysis consist of two hidden layers with 80 and 30 neurons respectively, coupled with a Rectified Linear Unit (ReLU) activation function, for the initial neural network model. The ReLU activation function is a popular choice in deep learning models due to its ability to efficiently compute gradients during backpropagation.

For the optimized neural network model,four hidden layers with 80, 30, 20, and 10 neurons were incoperated, also utilizing a ReLU activation function. The additional hidden layers enable the network to capture more complex patterns in the data, which could lead to improved performance.

Both models used the binary crossentropy loss function and Adam optimizer.Also, they were trained over a period of 15 epochs. The initial model demonstrated an accuracy of 72.6% when tested on the data, while the optimized model achieved an accuracy of 72.5%. Adding the additional hidden layers in the optimized model may enable the network to learn more abstract features, which could help it generalize to new data points.

# Summary
Our deep learning neural network did not perform as well as we had hoped, with an accuracy of less than 75%. To try and improve the model, we could consider using a Random Forest classifier, which is specifically designed for binary classification. Additionally, increasing the amount of data available for training could help the model identify more patterns and relationships within the data. Adjusting the hyperparameters of the neural network, trying different algorithms or ensembles, and exploring transfer learning are also potential options to improve the model's performance.
