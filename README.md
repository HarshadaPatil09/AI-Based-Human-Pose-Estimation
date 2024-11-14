**AI-Based Human Pose Estimation**

**Overview**
This project focuses on human pose estimation using keypoint data from joint positions, specifically tailored for analyzing running poses in sports.
By leveraging deep learning techniques, the model identifies and assesses the coordinates of key joints such as ankles, knees, hips, shoulders, and elbows, enabling a precise evaluation of an athlete's form during running.

**Project Highlights**
Dataset: The model was trained on a dataset comprising 17,372 samples, each annotated with key joint positions (X, Y coordinates) across various body parts like ankles, knees, hips, shoulders, and wrists.
Model: A deep learning model was developed using TensorFlow/Keras, utilizing fully connected layers to predict performance improvements based on detected keypoint coordinates.
Objective: The primary goal is to help athletes and coaches improve running form by analyzing the joint positions for optimized performance and injury prevention.

**Key Features**
Keypoint Detection: Uses key joint coordinates to estimate human poses, focusing on sports-specific movements.
Performance Evaluation: Helps identify areas of improvement in running form based on joint alignment and movement patterns.
Scalability: Designed for real-time pose analysis in sports applications with potential extensions for other activities.

**Results**
The model achieved high accuracy in identifying improvement areas, with a precision score of 94% and an overall accuracy of 93% on the test set.
These results demonstrate the model's capability to analyze key joint positions effectively for sports pose estimation.
