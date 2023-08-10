# Deep-fake-Detection

# Objective:

The primary objective of the Our project is to develop advanced and robust techniques for detecting and verifying the authenticity of facial images and videos, with the ultimate goal of effectively discerning between real and fake content. Through innovative algorithm design and comprehensive dataset analysis, we aim to provide a comprehensive and reliable solution to the escalating concerns surrounding the proliferation of deepfake technology. By leveraging machine learning methodologies, our project seeks to contribute significantly to the enhancement of digital media forensics, bolstering trust and accuracy in visual content across various applications, including social media, journalism, and law enforcement

# Motivation:

In an era characterized by the rapid evolution of digital media and the widespread accessibility of powerful content creation tools, the proliferation of deepfake technology has introduced a formidable challenge to the integrity of visual information. The alarming potential for malicious manipulation and the dissemination of misleading or fabricated content poses significant risks to society, ranging from the erosion of public trust to the distortion of factual narratives. As the boundaries between reality and fabrication become increasingly blurred, it is imperative to address this issue head-on.

# Workflow

1. Data Loading and Preprocessing: Load and preprocess the training and test image data. Data augmentation techniques are applied to the training data to increase the diversity of the dataset. We displayed 10 images of both real and fake images.

2. Model Selection: Build our own customizable model and Choose a pre-trained model to serve as the base for the evaluation of the image classification task. In this case, the ResNet model.

3. Compile the Model: Compile both the model by specifying the loss function, optimizer, and evaluation metrics.

5. Training: Train the model using the pre-processed training data.

6. Evaluation: Evaluate the trained model on the pre-processed test data to assess its accuracy and performance using a classification report and confusion matrix

7. Prediction and Analysis: Generate predictions on the test data, calculate a classification report, and create a confusion matrix to analyze the model's performance.


# Obervations:

> It is noticeable that even though the pre-trained model has less accuracy even below 50% yet it provides the right output as well as in less time compared to our model

> In order to increase the accuracy of our model we could diversify the dataset and improve the data augmentation technique


Dataset: https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection 

