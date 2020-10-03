# MaskDetection-COVID-19

---

## Introduction

---

MaskDetection-COVID-19 is a project that aims to solve the problem of identifying if someone has worn a mask or not. It is based on Convolutional Neural Network Architecture(CNN) and it is trained and integrated with computer vision technology to actively identify that if some user has worn a mask or not. 

---

### Neural Network Architectural Details:

---

* First Hidden Layer:
  * Convolution Layer: 200 Neurons(3X3)
  * Activation Function: RELU
  * Max Pooling Layer (2X2)
* Second Hidden Layer:
  * Convolution Layer: 100 Neurons(3X3)
  * Activation Function: RELU
  * Max Pooling Layer (2X2)
* Final Layer: 
  * Dense Layer: 50 neurons
  * Dropout
* Output Layer:
  * Dense: 2 neurons 
  * Activation: Softmax Transform
  * Loss: Categorical Crossentropy
  * Optimizer: Adam
* Model Results:
  * Accuracy: 0.9492
  * Loss: 0.1332
 
### Usage:

---

Clone the repo and run the .ipynb notebooks in the order of 

* dataPreprocessing.ipynb 
* CNNTraining.ipynb
* maskDetection.ipynb


> The code is well-commented and the details regarding implementation, CNN architecture related details are deliberated.
For further reference, check out the snippets of code from <a href="https://github.com/HariAcidReign/ImageRecognition">Image Recognition</a>, and <a href="https://github.com/HariAcidReign/DS-and-ML-Resources/blob/master/CNN%20using%20TF%20and%20Keras.ipynb">CNN with Keras and Tensorflow</a> repositories. 

### Libraries used:

---

* cv2 (Computer Vision Library)
* Tensorflow + Keras
* Numpy
* sklearn
* Matplotlib




