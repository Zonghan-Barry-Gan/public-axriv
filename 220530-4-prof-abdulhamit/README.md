This is a commit for the code showing to prof. Abdulhamit. including:
1. 83% of balanced accuracy on breast histopathology images, using soft attention model
2. 83% of balanced accuracy on breast histopathology images, using mobilenetV2+ANN with extreme low learning rate, However, with such learning rate, only 300 samples were allowed on Kaggle.
3. The detection and correction of the common bug in shuffling data for breast histopathology dataset on Kaggle. This bug is originally from https://www.kaggle.com/code/ayushv322/breast-cancer-detection-vgg16 and "infect" other codes for the dataset on kaggle, by shuffling the data-label combined array using random.shuffle
