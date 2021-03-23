# CNN-Dog-Cat-Classification

Welcome to the TensorFlow branch. The CNN here was made using the Tensorflow and Keras libraries.

Please find the dataset here: https://www.kaggle.com/c/dogs-vs-cats

## Tensorflow CNN
The CNN had the following layer order: Convolutional, Maxpooling, second Convolutional, flattening for the ANN, and finally a fully connected layer to an output layer of 1 neuron.
The Adam optimizer was selected and binary crossentropy loss was calculated. For more details, please look at my code on Github:

## Results
After 40 epochs, the training accuracy was 92.6%. However, the validation accuracy was much lower at 78.6%, meaning overfitting occured. To improve this, dropout layers, batch normalization, and more convolutional layers should be used. Due to lack of computational power and time (no GPU), these improvements were added and tested on the PyTorch CNN instead.
