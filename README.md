# Hindi-Alphabet-Classifier
The classifier takes images of hindi alphabet and classifies it into five categories.
The categories are : Ka, Kha , Ga, Gha, Kna

Model Used : Scequential Model (From Keras Library : Deep Learning Approach)

About Model 0:
-> 1 Convolutional 2D Layer
->Max Pooling Layer
-> 2 Dense Layers
Learning Rate : 0.01
Optimiser = Adam
EPOCH : 32
ACCURACY : 0.95
----------------------------------------------------------------
About Model 1 [ FINAL MODEL]:
-> Two Convolutional 2DLayers are added with Activation being Relu.
-> Max Pooling 2D Layer is added 
->Two dense layers are added (activation : Relu and Softmax)
EPOCH :10
->1. Learning rate= 0.001,optimiser : SGD
ACCURACY : 0.611 {Probably because of the low learning rate}

2. Learning Rate : 0.01 , OPTIMISER : ADAM
ACCURACY :


---------------------------------------------------------------

PROBLEMS FACED : 

Data Reading and formation.
Initially Trying with just x_train : Image array data
-> Read about Image Data Generation wih keras : Put the data more into place ( Fitting x_train and x_test data accordingly)

Which approach to take up: 

Read various methods of implementation of classifier, Deep Learning using CNN showing the best result in various strategy, hence finally deciding to impement this.

Experimentation with various models types:

Several models implemented, with experimentaton on layers.
Model 0 and Model 1 shown.

Learning rate and Activation function:
Learning rate : Tried various learning rates : 0.01 being most suitable
Optimiser :   Tries Adam , SGD : Adam giving beter results
Loss Function : sparse_categorical_crossentropy {Read to be the best for categorical classification}
