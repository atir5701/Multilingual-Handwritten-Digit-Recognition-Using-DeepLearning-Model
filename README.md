# Multilingual-Handwritten-Digit-Recognition-Using-Multiplexer-Based-Deep-Learning-Model

This project tackles the project of handwritten digit recognition. The approach is used to classify digits for 5 different languages using a multiplexer-based approach. Recognizing handwritten digits poses a significant challenge in machine learning and image processing due to the inherent variations in individual writing styles, sizes, curves, strokes, and interpretations. This research presents an innovative method for classifying handwritten digits in various languages, including Urdu, Gujarati, Hindi, and Bengali, using a multiplexer-based deep learning model. This approach streamlines the classification process and achieves 98.88% accuracy, offering a promising solution for recognizing handwritten digits in diverse linguistic contexts.

## Introduction 

Handwritten digit recognition is a challenging problem in machine learning and computer vision due to the diversity in writing styles, sizes, and strokes. This project aims to create algorithms and systems that can accurately transform handwritten digits into machine-readable representations. The proposed model successfully classifies digits in languages such as Urdu, Gujarati, Hindi, Bengali, and English using a unique “Multiplexer Model”.

## Proposed Architecture
 - ### Dataset Description
  The dataset includes handwritten digit images from five languages: Hindi, Urdu, Gujarati, Bengali, and English. The dataset is divided into training, validation, and testing sets. Each image is preprocessed to ensure uniformity and resized to 32x32 pixels.
  
 - ### Proposed Approach
  The proposed approach involves training five language-specific models for Hindi, Urdu, Gujarati, Bengali, and English, as well as a language classifier model on a combined dataset. The system functions akin to a multiplexer, where the language classifier model acts as the selection line to choose the appropriate digit classifier for a given input digit, enhancing prediction accuracy.
  
-  ### Architecture
  The deep learning model consists of multiple convolutional blocks followed by fully connected layers. The architecture is used for both language recognition and digit recognition phases, with minor adjustments for specific layers.
  
  Language Classifier: Identifies the language associated with a digit.
  Digit Classifier: Recognizes digits for each specific language.

  The overall architecture is shown in the figure below

## Installation 
  - Clone Repo
      - git clone <repository_url>
      - cd multilingual-handwritten-digit-recognition
  - Python
  - Tensorflow
  - Pandas
  - Numpy
  - Matplotlib
  - Sklearn
      
