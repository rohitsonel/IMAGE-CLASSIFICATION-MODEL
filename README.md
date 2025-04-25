# IMAGE-CLASSIFICATION-MODEL

COMPANY : CODTECH IT SOLUTION

NAME : ROHIT SONEL

INTERN ID : CT4MHBA

BOMAIN : MACHINE LEARNING

BATCH DURATION : DECEMBER 30TH,2024 TO APRIL 30TH,2025

MENTOR NAME : NEELA SANTHOSH KUMAR

#DESCRIPTION OF TASK 3

The goal of this project is to build a binary image classification model capable of distinguishing between lions and tigers using deep learning techniques. Leveraging the TensorFlow/Keras framework, a custom convolutional neural network (CNN) was developed from the ground up and trained on a labeled dataset of lion and tiger images.
The dataset is organized into separate directories for each class (lions/ and tigers/) and processed using ImageDataGenerator with normalization and augmentation techniques such as horizontal flipping and scaling. Images are resized to 224x224 pixels and split into training and validation sets with an 80/20 ratio.
The model architecture consists of three convolutional layers with ReLU activation and max pooling, followed by a flattening layer and two dense layers, the final one using a sigmoid activation for binary classification. The network is compiled using the Adam optimizer and binary crossentropy loss, and trained for 20 epochs with real-time validation.
Performance is evaluated through accuracy metrics and plotted across training epochs. Additionally, a utility function is implemented to classify new images and return predictions in human-readable form (i.e., "Lion" or "Tiger").
The final trained model is saved in .h5 format, making it suitable for deployment or future integration into applications requiring wildlife classification capabilities. This project demonstrates how custom CNNs can perform well on fine-grained image classification tasks without relying on pre-trained models.
