# Text-classification
Using KNN and comparing it with neural networks to understand what number what written by children ina writing test. 
Also performing Gradient Boosting to evaluate and choose the best model

Summary:

The Python script loads a dataset called "letters.csv" and performs exploratory data analysis on it. It then applies the K-Nearest Neighbor, Neural Network, and Gradient Boosting models to predict the labels of the data entries. The data contains numerical values, and the label represents the letter associated with each set of values.

Results:

The K-Nearest Neighbor model was trained on 80% of the data and tested on the remaining 20%, with K=3. The accuracy of the KNN model on the test set was 92.35%, and the classification report showed good precision and recall for all labels.

The Neural Network model was also trained on 80% of the data, using a multilayer perceptron with 3 hidden layers, ReLU activation function, and stochastic gradient descent optimizer. The accuracy of the neural network model on the test set was 98.14%, and the classification report showed high precision and recall for all labels.

Finally, the Gradient Boosting model was applied to the data using default parameters, achieving an accuracy of 96.23% on the test set. The classification report showed good precision and recall for all labels.

Overall, the models achieved high accuracy and performed well in predicting the labels of the data entries.
