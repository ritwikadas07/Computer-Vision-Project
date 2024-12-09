# Real-Time Sign Language Prediction

202403_Intro to Computer Vision_CSCI_6527_10_Final Project

## Acknowledgment
This blog post was created by Ritwika Das (GWID: G30941802) and Aditi Vyas (GWID: G40802010) under the guidance of Professor Robert Pless for the course Introduction to Computer Vision (CSCI 6527_10).

## Main Idea
The main focus of this project was sign language prediction using LSTM networks and MediaPipe technology. We aimed to accurately interpret common sign language phrases like "I love you", "thanks", and "hello" in real-time.

## Overview
We developed a system that utilized the MediaPipe Holistics framework to identify human gestures and predict corresponding sign language phrases. This involved extensive data handling, machine learning modeling, and real-time predictive analysis.

## Process
1. Dependencies necessary for running the project were imported and installed.
2. Keypoints were captured using the MediaPipe Holistics model to detect holistic body landmarks from video inputs.
3. Keypoint values were extracted for detailed gesture analysis.
4. Folders for data collection were set up corresponding to the phrases "I love you", "thanks", and "hello".
5. Keypoint values for each phrase were collected for training and testing the model.
6. Data was preprocessed to create labels and features suitable for machine learning models.
7. An LSTM neural network was built and trained to classify the different gestures based on the collected data.
8. Predictions were made using the trained model to evaluate its performance.
9. The model weights were saved post-training for future reference and use.
10. The model's performance was evaluated using a confusion matrix and accuracy metrics to assess its precision.
11. The system was tested in real-time to ensure it functioned correctly under live conditions.

## Progress
We have completed each of the steps in the project. However, the model requires further training to enhance its precision and ensure more accurate gesture recognition.

## Future Work
Upon achieving satisfactory prediction accuracy, we plan to extend the project's functionality by implementing a text-to-speech conversion system. This will enable the application to not only recognize gestures but also convert them into spoken words, increasing its utility for communication purposes.
