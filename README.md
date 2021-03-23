# CNN-Dog-Cat-Classification

Welcome to the AlexNet branch. The CNN here was made using the PyTorch library.

Please find the dataset here: https://www.kaggle.com/c/dogs-vs-cats

To get a copy of my model, please go here as it was too large to upload on Github: https://drive.google.com/file/d/1FInIgKE1s7caEuuYHt6KeOpxXOVrCBFk/view?usp=sharing 

## AlexNet
AlexNet already came with pre-trained weights. However, AlexNet is built to have 1000 classification outputs. To implement it for Dog-Cat classification, the final output was reduced to 2.

## Results
After 40 epochs, the training accuracy was found to be 91.6% and test accuracy was even better at 95.5%. This is already performing far better my PyTorch CNN model which had a training accuracy of 77.5% and test accuracy was 76.6%. To improve my CNN model, more Convolutional layers can be added similar to AlexNet, as well as optimizing specific attributes such as kernel size and strides.

Similar to my CNN's results, the confusion matrix below suggests that cats are still misclassified as dogs more often. An explanation for this may be due to cats having pointy ears similar spitz type dogs such as Huskies and Jindos. As such, the model may mislabel them as dogs (and the same could go for said dogs being mislabelled as cats).
