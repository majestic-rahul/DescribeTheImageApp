# DescribeTheImageApp

## Overview

This repository contains the source code for an Android app that generates image captions using deep learning techniques. The app is designed to help visually or aurally impaired individuals comprehend and navigate their surroundings better by providing natural language descriptions for images captured with a smartphone camera.

## App UI

![image](https://github.com/majestic-rahul/DescribeTheImageApp/assets/79097971/81a40cba-1ae4-411e-9520-e07a0a8f90a2)

![image](https://github.com/majestic-rahul/DescribeTheImageApp/assets/79097971/2729edbb-f4ee-4553-b38c-a5f133d2e159)

![image](https://github.com/majestic-rahul/DescribeTheImageApp/assets/79097971/3d6b0e60-5cd9-4f50-99b3-ba2c177216db)

![image](https://github.com/majestic-rahul/DescribeTheImageApp/assets/79097971/7a9606c3-b022-4800-908f-cb218537eb70)


## Motivation

People with visual or hearing impairments often face challenges in their daily lives due to inaccessible infrastructure and social issues. Simple tasks like shopping, traveling, or navigating their surroundings can become difficult for them. This app aims to enhance their quality of life by providing an intuitive tool for generating captions and descriptions for images.

## Proposed Solution Approach

The app combines two deep learning models: VGG16 for image feature extraction and LSTM for caption generation. VGG16 is a convolutional neural network (CNN) architecture that can identify objects and their features in images. On the other hand, LSTM (Long Short-Term Memory) is a type of recurrent neural network (RNN) used for sequential data modeling and natural language processing.

The process involves two steps:

1.) Extracting visual features from images using VGG16.

2.) Feeding these features into the LSTM model to generate descriptive captions.

The Android app is developed using Java and Android Studio, with a real-time Firebase Database used for storing the model's generated captions and the images that were clicked. This allows for easy retrieval of data for further analysis and real-time processing of photographs and captions.

## Results

The app was trained on the Flickr 8k dataset, which contains a large number of images with associated captions. The model was trained for 20 epochs, resulting in a BLEU score of 0.544012, indicating the accuracy of the generated captions.

## App Features

* User-friendly interface designed for visually and hearing impaired individuals.
  
* Image caption generation using VGG16 and LSTM models.
  
* Real-time Firebase Database integration for storing images and captions.
  
* Ability to choose images from the gallery or capture new images using the smartphone's camera.
  
* Option to read the generated caption out loud.
  
## Installation and Usage

To use the app, follow these steps:

* Clone the repository to your local machine.
  
* Open the project in Android Studio.
  
* Run the app on an Android device or emulator.

## Future Enhancements
  
In the future, the app will be enhanced to include the following features:

* Translation of captions into multiple languages.

* Support for iOS operating system.

* Improved user interface for a seamless experience.
  
