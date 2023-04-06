# MNIST Dataset

### Objective 
The objective was to train an image classifier from the Modified National Institute of Standards and Technology (MNIST) dataset. It is a dataset with 60,000 training and 10,000 testing samples of grayscale handwritten images of numbers between 0-9. The neural network model must be able to classify the handwritten numbers into one of ten possible classes. I chose the MNIST dataset because I thought it would be fun to train a classifier that could recognize handwritten images and predict their numerical value! 

### Sample Images

### Process
1) I began by importing several Machine Learning libraries from Keras and loading the dataset. Normally, the dataset would have to be split into training and validation sets, but the MNIST dataset provides both. I plotted the dataset into its 10 classes (0-9) to better visualize the task. The model would have to be able to distinguish between the black background pixels (0 bits) and the white pixels (255 bits) of the numbers. Therefore, the data—passed as a vector of 10—was normalized with this information in mind. 

2) The next step after preparing the data was creating the neural network model. The Sequential model served as a backbone for the input layers. It’s important to note that our output layer will contain 10 units for the 10 possible classes of numbers.

3) Rinse and repeat! The model has to be trained so that it may learn to categorize the numbers based on the images. Once I got the accuracy I sought,  predictions were made utilizing the highest probability made by the classifier to generate a number. In the final tuple, I tested the model with a randomized example and plotted the results. The randomized image was a handwritten six that was predicted and validated to in fact be the number six. 


### Results

The model was able to generate an accuracy of ~99.8%! 

This was a really fun and easy project to basically test out the "Hello World" of Machine Learning & Neural Networks! This was also my first time utilizing python for a project so it was definitely a learning experience. 
