# ML2 Final Project

## Purpose
This is a final project for a Machine Learning 2 course at University of Warsaw. It's main purpose was to create a neural network able to recognize whether a skin change is malignant (cancerous) or benign (non cancerous).
For now there is only one model but in the future the plan is to create a couple of different ones and test them. I'm also going to try and download a ready model and use it for classification

## File Description

### Archive

This is the folder containing all the training and test data. It contains raw jpg files showing different skin changes, both malignant and bening. The training data is 2600 pictures and testing data is 660 pictures. 

### Model 1 - 80% accuracy

This model contains multiple convolutional, max pooling and finally fully connected layers. It's final accuracy was around 78-80%, but the model turned out way too complicated. It utilizes Adam optimizer, learning rate schedule and early stopping schedule. 

#### Model architecture

### Model 2 - 88% accuracy

The second model with higher accuracy was the result of refining the original model. I introduced data augmentation, by randomly zooming and rotating the pictures in the training dataset. Using this operation, I was able to make the training dataset 3x larger. Thanks to this, the accuracy was raised by about 2-3%. Refining the model architecture and making it a smaller also made a difference and improved final accuracy. 

#### Model architecture 

## Running the model

To run the model all you need is download one of the jupyter notebook files. Data dowloading, model architecture, and other functions important for running the model are inside each of the notebooks. When creating the dataset using a dedicated function you may need to change the directory the data got downloaed to. 



