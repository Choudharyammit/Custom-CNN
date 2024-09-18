# Melanoma Skin Cancer Detection using Custom CNN

## Table of Contents

- [Introduction](#Introduction)
- [Project Workflow](#project-workflow)
- [Technologies Used](#technologies-used)
- [Results and Conclusions](#results-and-conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
  `

## Introduction

The goal of this project is to develop a custom Convolutional Neural Network (CNN) to accurately classify skin lesions into 9 categories, focusing on the early detection of melanoma. This solution aims to assist dermatologists in diagnosing melanoma, potentially saving lives through early detection.

## Project Workflow

    1.	Data Preprocessing:
    •	Load images from the dataset, resize them to 180x180 pixels, and normalize pixel values.
    2.	Dataset Creation:
    •	Split the data into training and validation sets with a batch size of 32.
    3.	Data Visualization:
    •	Visualize one sample image from each of the 9 classes for better understanding.
    4.	Model Building:
    •	Construct a custom CNN model to classify images into 9 categories.
    •	Normalize image pixels and select appropriate loss functions and optimizers.
    •	Train the model for 20 epochs.
    5.	Model Evaluation:
    •	Analyze the training history for evidence of underfitting or overfitting.
    6.	Data Augmentation:
    •	Apply rotation, zoom, and flip augmentation techniques to improve the model’s generalization.
    •	Retrain the model on the augmented dataset for 20 epochs and assess improvements.
    7.	Class Imbalance Handling:
    •	Use the Augmentor library to address imbalances in class distribution.
    •	Retrain the model on the adjusted data for 30 epochs.
    8.	Final Evaluation:
    •	Evaluate the model’s performance and provide findings related to accuracy, precision, and recall.

## Technologies Used

- Python 3.x
- TensorFlow 2.x
- Keras
- Augmentor (for data augmentation)
- Matplotlib (for visualizations)

## Results and Conclusions

- **Findings**:
  - Initially, the model showed [overfitting/underfitting], which was addressed through data augmentation.
  - Class imbalance was rectified, and the model performed better on underrepresented classes.
  - The final model performed well, showing [accuracy/performance metrics] after training with augmented and balanced data.

## Acknowledgements

- This project was inspired by deep learning applications in medical imaging.
- The dataset was provided as part of [competition/tutorial/reference].
- Thanks to the developers of TensorFlow and Augmentor libraries for their contributions.

## Contact

Created by [@Choudharyammit](https://github.com/Choudharyammit) - feel free to contact me for any questions.

---
