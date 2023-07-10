# Steak-or-pizza-detection
The data contains different images of pizza and steak, i built a model to predict what food (pizza or steak) it will show
This GitHub repository contains code for a deep learning project that focuses on classifying images of pizza and steak. The code performs the following tasks:

1. Downloads a zip file containing pizza and steak images from a Google Cloud Storage bucket.
2. Extracts the images from the downloaded zip file.
3. Lists the directories and files in the extracted image dataset.
4. Calculates the number of steak images in the training set.
5. Retrieves the class names from the subdirectories of the training dataset.
6. Visualizes a random image from the training dataset.
7. Preprocesses the image data by scaling the pixel values between 0 and 1.
8. Sets up the training and test directories.
9. Uses the `ImageDataGenerator` class from TensorFlow to generate batches of augmented image data for training and validation.
10. Defines and trains multiple convolutional neural network (CNN) models with different architectures and hyperparameters.
11. Evaluates the performance of the trained models on the test dataset.
12. Plots the loss and accuracy curves for the training and validation data.
13. Demonstrates data augmentation techniques by showing original and augmented images.
14. Compares the performance of the models trained with and without shuffled augmented data.
15. Provides a summary of each trained model's architecture.
16. Downloads an example image of steak for demonstration purposes.

The code is well-documented and includes explanations and comments to guide the reader through the different steps. 
