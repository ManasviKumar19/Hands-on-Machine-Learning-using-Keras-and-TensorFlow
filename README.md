# Hands-on-Machine-Learning-using-Keras-and-TensorFlow

This repository contains Jupyter Notebooks for learning MachineLearning using Keras and TensorFlow.

In chapter 10, we start from the basics of Deep learning and learn the working of Artificial Neural Networks with Keras and train our very first Neural Network.

In chapter 11, we train Deep Neural Networks and look at the different challenges that one may face while trying to train a Network and how to overcome those challenges.

In chapter 12, we build custom layers, custom functions, custom metrics and custom Models for our specific use cases.

In chapter 13, we look at how we can load and pre-process data with TensorFlow on the fly and learn about the Data API and TRF.

In chapter 14 we will explore where CNNs came from, what their building blocks look like, and how to implement them using TensorFlow and Keras. Then we will discuss some of the best CNN architectures, as well as other visual tasks, including object detection (classifying multiple objects in an image and placing bounding boxes around them) and semantic segmentation (classifying each pixel according to the class of the object it belongs to).

In chapter 15 we will first look at the fundamental concepts underlying RNNs and
how to train them using backpropagation through time, then we will use them to
forecast a time series. After that we’ll explore the two main difficulties that RNNs
face:
• Unstable gradients (discussed in Chapter 11), which can be alleviated using various techniques, including recurrent dropout and recurrent layer normalization, 
• A (very) limited short-term memory, which can be extended using LSTM and GRU cells

RNNs are not the only types of neural networks capable of handling sequential data: for small sequences, a regular dense network can do the trick; and for very long sequences, such as audio samples or text, convolutional neural networks can actually work quite well too. We will discuss both of these possibilities, and we will finish this chapter by implementing a WaveNet: this is a CNN architecture capable of handling sequences of tens of thousands of time steps.