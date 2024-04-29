# DSCI_6011_02-FINAL-PROJECT by Harshith Reddy, Raja shekar Reddy, Sushma Sindhe and Sai Swaroopa.
# Project: Drowsiness Detection System
## Overview:
A drowsiness detection system is a technology that monitors a person's level of alertness during activities like driving. It uses sensors to track indicators such as eye movements, facial expressions, and steering behavior. Machine learning algorithms analyze this data to detect signs of drowsiness, triggering alerts to the driver to prevent accidents.

## Project Components:
### Dataset:
we have taken our dataset from kaggle
1.We have done Image Processing
  our preprocessing will include¶
  Detecting faces from images
  Drawing landmarks on our images to increase performance
  Resizing our images
  LabelEncoding
  Image Augmantation
2.Splitting the data
3.Data Augmentation
4.Deep Learning Models

VGG16: VGG16 model for gender classification and age prediction involves adapting a pre-trained convolutional neural network (CNN) to these specific tasks. This approach benefits from transfer learning, where knowledge from a model trained on a large dataset (like ImageNet) is leveraged to improve performance on a related but smaller dataset. VGG16 Model weights can be downloaded online and can be imported to the notebook.

Process (step by step):
The implementation is done on Kaggle platform.

Importing all necessary libraries and modules.

Importing the dataset by accessing the link.

Converting images into dataframes.

Performing Exploratory Data Analysis.

Filtering the dataset images using the Gaussian, Mean, Median, Wiener filters.

Storing filtered images and creating respective dataframes.

Evaluating the effect of filtering by calculating the Structure Similarity Index, Peak Signal to Noise Ratio, Mean Square Error.

Train-test splitting of the dataframes.

Feature extraction of the dataframes.

Model building for all 5 dataframes. Using the activation layers, optimization layers etc is done here.

Training the models.

Evaluation of models by calculating the Accuracy, precision, recall for Classification task and Mean Square Error, Mean Absolute Error for Regression task.

Comparing the performance of all the models for both the architectures and checking the effect of filtering on the overall improvement of the performance of the built models.

Conclusion:
This project offers a comprehensive exploration of Gender Classification and Age Prediction using deep learning, providing a valuable resource for researchers and students interested in computer vision, deep learning, and image processing. The comparison of different models offers insights into their strengths and weaknesses, guiding future research in the field. The well-documented code and usage instructions ensure accessibility and reproducibility for other researchers and enthusiasts.
