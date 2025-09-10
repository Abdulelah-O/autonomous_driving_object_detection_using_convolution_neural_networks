#  Autonomous Driving Object Detection Using Convolutional Neural Networks (CNNs)


## 1. Introduction

**Object detection** is a fundamental task in autonomous driving, involving the identification and localization of various objects in a real-time environment. These objects can include pedestrians, vehicles, traffic signs, and other elements that are crucial for safe navigation.

Convolutional Neural Networks (CNNs) have proven to be highly effective in tackling this complex task. CNNs are a type of deep learning architecture that is specifically designed to process and analyse image data.

## 2. Input Dataset

KITTI is a dataset for autonomous driving developed by the Karlsruhe Institute of Technology and Toyota Technological Institute at Chicago. It is a collection of images and LIDAR data used in computer vision research, such as stereo vision, optical flow, visual odometry, 3D object detection, and 3D tracking.

The object detection and object orientation estimation benchmark consist of 7481 training images and 7518 test images, comprising a total of 80.256 labelled objects. belonging to 9 different classes including **car**, **don’t care**, **van**, **pedestrian**, **cyclist**, **truck**, **misc**, **tram**, and **person sitting**.

<img width="940" height="270" alt="image" src="https://github.com/user-attachments/assets/60149468-637b-4d9c-aaa9-b36766e588ab" />


## 3. Data splitting

The dataset was split into **training** and **testing sets** using an **80/20** ratio, where **80%** of the data was used for **training** and **20%** for **testing**. This ratio was chosen to ensure that the model has enough data to learn from while keeping a reasonable amount for evaluating its performance. The training set provides a substantial amount of data for the model to recognize patterns and learn effectively, while the testing set offers sufficient data points to accurately evaluate the model's performance.

