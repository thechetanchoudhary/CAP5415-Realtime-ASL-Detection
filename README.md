# Real-Time Sign Language Detection

## Problem Definition

American Sign Language or ASL is the official sign language for deaf or hearing-impaired individuals in the United States and Canada. ASL is a sophisticated language with its own grammatical rules. However, ASL is not widely understood, creating a communication barrier between deaf and hearing individuals. Computer-based vision technologies can bridge this gap.

Our project aims to develop a computer vision system that can recognize ASL letters in real-time from a live webcam feed. This technology can be used for real-time translation of sign language into spoken languages and for creating educational materials in sign language.

## Dataset

The proposed computer vision system is trained using the ASL Alphabet dataset, which can be found [here](https://www.kaggle.com/datasets/grassknoted/asl-alphabet). This dataset consists of approximately 87,000 training images and 29 test images. The images are 200x200 pixels and are divided into 29 classes, including the 26 A-Z letters, SPACE, DELETE, and NOTHING. Three additional classes support real-time processes and classifications.

## Technologies Used

Our project leverages the following technologies:

- Python
- PyTorch
- Flask
- HTML
- CSS

## Project Team

- Chetan Choudhary
- Venkata Rohan Bharadwaj Bandarupalli
- Zackary Keiner

## Project Phases

We will approach and solve the problem in the following steps:

1. **Data Preprocessing**: We will preprocess the ASL Alphabet dataset to ensure uniform image size, format, and quality. This may involve resizing, converting to grayscale, and intensity normalization.

2. **Feature Extraction**: A feature extractor will be trained to extract features from the preprocessed images, representative of ASL letters and robust to changes in lighting, background, and angle.

3. **Classification**: We will employ various deep learning classifiers such as YOLOv5, YOLOv8, Faster R-CNN, and Mask R-CNN for classification. The choice of the best classifier will be based on a balance between efficiency and predictive power, aiming for high accuracy in real-time with fast response times.
