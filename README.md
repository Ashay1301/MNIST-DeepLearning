# MNIST Deep Learning


An implementation of multilayer neural network using keras with an Accuracy: mean=96.058 

## Description:

The goal of this project was to become familiar with deep networks. For this project, I have implemented deep convolutional networks to classify handwritten digits. I have also carefully analyzed the hyperparameter tuning and assessed the performance of the network with different configurations.

## Network Model
<img width="240" alt="image" src="https://github.com/Ashay1301/MNIST-DeepLearning/assets/69242688/cf3e014e-5a23-4c01-a8c9-8629d8d4046e">

## Output
<img width="468" alt="image" src="https://github.com/Ashay1301/MNIST-DeepLearning/assets/69242688/62a53d38-55a2-48ca-8aa2-7d51f6213542">
<img width="468" alt="image" src="https://github.com/Ashay1301/MNIST-DeepLearning/assets/69242688/3f83d896-d6da-4317-bb50-992fd9c0d3e4">



## Steps:

1. Import the libraries and load the dataset: Importing the necessary libraries, packages and MNIST dataset
2. Preprocess the data
3. Create the model
4. Train and Evaluate the Model
5. Saving the model
6. Make Predictions

## Transfer Learning to Greek Letters

the Greek letter dataset specified in the task description was downloaded and prepared for compatibility with the existing network configuration. In order to enable the system to recognize Greek letters, the pre-trained model from the previous step was loaded. The gradient parameters were frozen, and the last linear layer was modified to have 3 output nodes instead of 10. Training and testing were conducted using all 27 images. Notably, the model achieved a 96% accuracy rate after several epochs; however, it exhibited difficulty in further training beyond this point.
<img width="468" alt="image" src="https://github.com/Ashay1301/MNIST-DeepLearning/assets/69242688/ac42e39a-7b72-4df6-9813-f3be14119887">




# Resources:
[Deep Learning Introduction](https://medium.com/r/?url=https%3A%2F%2Fwww.forbes.com%2Fsites%2Fbernardmarr%2F2018%2F10%2F01%2Fwhat-is-deep-learning-ai-a-simple-guide-with-8-practical-examples%2F%235a233f778d4b)<br/>
[Install Tensorflow](https://medium.com/@cran2367/install-and-setup-tensorflow-2-0-2c4914b9a265)<br/>
[Why Data Normalizing](https://medium.com/@urvashilluniya/why-data-normalization-is-necessary-for-machine-learning-models-681b65a05029)<br/>
[One-Hot Code](https://medium.com/r/?url=https%3A%2F%2Fmachinelearningmastery.com%2Fwhy-one-hot-encode-data-in-machine-learning%2F)<br/>
[Understanding of Convolutional Neural Network (CNN)](https://medium.com/@RaghavPrabhu/understanding-of-convolutional-neural-network-cnn-deep-learning-99760835f148%20https://www.youtube.com/watch?v=YRhxdVk_sIs)<br/>
[CNN layers](https://medium.com/r/?url=https%3A%2F%2Fwww.tensorflow.org%2Fapi_docs%2Fpython%2Ftf%2Fkeras%2Flayers%2FLayer)<br/>
[K-cross Validation](https://medium.com/r/?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DTIgfjmp-4BA)<br/>
[Plotting Graphs](https://medium.com/r/?url=https%3A%2F%2Fmatplotlib.org%2Fapi%2Fpyplot_api.html)<br/>
