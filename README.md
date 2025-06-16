#Traffic Sign Recognition Using CNN (GTSRB Dataset)

This project uses a Convolutional Neural Network (CNN) to classify traffic signs using the GTSRB dataset.

##Dataset used

-> Name : GTSRB (German Traffic Sign Recognition Benchmark) dataset

-> Source : Downloaded from: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

-> Includes :
       -> Labeled train and test images
       -> CSV files with class labels and metadata

##Model Architecture

-> 2 Conv2D + MaxPooling layers
-> Dropout regularization
-> Dense layers with softmax output
-> Optimizer: Adam
-> Loss: Categorical Crossentropy

##Results

-> Validation Accuracy: ~99%
-> Test Accuracy: 98.8%
-> Visualizations:
  -> Accuracy & Loss Graphs over Epochs
  -> Confusion Matrix

#License & Credits
->Dataset: GTSRB - Kaggle
->Model trained using TensorFlow Keras in Google Colab
