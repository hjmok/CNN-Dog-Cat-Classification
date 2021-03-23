# CNN-Dog-Cat-Classification

Welcome to the PyTorch branch. The CNN here was made using the PyTorch library.

Please find the dataset here: https://www.kaggle.com/c/dogs-vs-cats


## PyTorch CNN
The CNN had the following layer order: Convolutional, Maxpooling, second Convolutional, second Maxpooling, flattening for the ANN, and finally two fully connected layer to an output layer of 1 neuron. In addition, drop out layers were also used to improve results.
Similar to the Tensorflow CNN, the Adam optimizer was selected and the crossentropy loss was calculated.

## Results
TENSORFLOW CNN RESULTS
After 40 epochs, the training accuracy was found to be 77.5%. The validation accuracy was consistent with this at 76.6%, which is also supported by the accuracy plot below. This shows that the addition of dropout layers and batch normalization has helped to reduce overfitting from the Tensorflow results.
In addition, the confusion matrix suggests that cats are more likely to be falsely predicted as dogs. An explanation for this may be due to cats having pointy ears similar spitz type dogs such as Huskies and Jindos. As such, the model may mislabel them as dogs (and the same could go for said dogs being mislabelled as cats).
