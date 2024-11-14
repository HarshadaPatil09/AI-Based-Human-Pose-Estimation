**AI-Based Human Pose Estimation**

**Overview**

This project focuses on human pose estimation using keypoint data from joint positions, specifically tailored for analyzing running poses in sports.
By leveraging deep learning techniques, the model identifies and assesses the coordinates of key joints such as ankles, knees, hips, shoulders, and elbows, enabling a precise evaluation of an athlete's form during running.

**Objective**

The primary objective of this project is to develop a human pose estimation model that focuses on analyzing key joint coordinates, specifically for sports analytics in activities like running. Unlike traditional pose estimation systems that rely on video data, this model is built using only keypoint coordinates of essential joints such as the ankles, knees, hips, shoulders, and elbows. The aim is to provide a tool that can accurately detect and analyze these keypoints to deliver insights on running posture and biomechanics.
By doing so, this project seeks to enhance athletic performance by identifying inefficiencies in running form, which can be crucial for optimizing training outcomes. Additionally, it aims to contribute to injury prevention by analyzing the alignment of key joints, thereby helping coaches and athletes correct their posture and reduce the risk of injuries. Furthermore, the model is designed to be scalable for integration into real-time sports analytics systems, providing immediate feedback to athletes during training sessions, thus supporting both performance improvement and safety.

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
