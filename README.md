# DSCI_6011_02-FINAL-PROJECT by Harshith Reddy, Raja Shekar Reddy, Sushma Sindhe and Sai Swaroopa 
# Project: Drowsiness Detection System
## Overview:
The goal of the Drowsiness Detection System project is to address the growing issue of drowsy driving, a risky phenomena that puts road safety at serious risk all over the world. When someone drives when tired or drowsy, it hinders their ability to stay awake and respond rapidly to changing road conditions. This is known as drowsy driving. The goal of this research is to create a system that can identify driver drowsiness in real time, preventing accidents and maybe saving lives.
Project Components:
Dataset:
5 V’s of Data; Volume, Variety, Velocity, Veracity, Value are checked to ensure right set of data is collected for the problem statement. The dataset consists of 20000 face images with age, gender, ethnicity as the features. It has an age span of 0 to 116 years. It is a structured, labeled dataset.

Dataset link: https://susanqq.github.io/UTKFace/

Pre-Processing of Dataset images:
Noise Filtering dataset images using various filters like Gaussian, mean, median, and Wiener filters is a common preprocessing step in many image processing and computer vision tasks. These filters can help reduce noise, improve image quality, or prepare images for further processing like feature extraction or classification.

Evaluating the effectiveness of noise filtering techniques on images is crucial to determine how well the filters preserve image details while removing noise. The Structural Similarity Index (SSIM), Mean Squared Error (MSE), and Peak Signal-to-Noise Ratio (PSNR) are commonly used metrics for this purpose.

Deep Learning Models:
CNN Model: CNNs, or Convolutional Neural Networks, are a class of deep neural networks that are especially effective in visual imagery analysis. They have been successfully applied in various tasks such as image and video recognition, image classification, medical image analysis, and, gender classification and age prediction.

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
