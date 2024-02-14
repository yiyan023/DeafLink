# DeafMute 👋

## Inspiration ✨
With over 300 sign languages and 7000 dialects, the lack of translation resources bridging these forms of communication has been a significant barrier for deaf and speech-impaired communities. Despite the abundance of applications that can convert one verbal dialect to another, the world is still in search of a product that is capable of creating sign language accessibility. With DeafMute, this unique translation application that can help others to understand sign language and break down these language barriers one by one.

## What does it do? 👩‍💻
- By incorporating object detection and computer vision, DeafLink enables the user to gain real-time translation of ASL to English

## How was it built? 🔨
- This application was created by training a machine learning model to recognize different ASL hand signs using OpenCV, Mediapipe & Scikit-Learn
- Specifically, OpenCV was used to enable computer vision for data collection & ML training & Mediapipe was used to enable 20+ hand landmark estimations to increase recognition accuracy.

![100DE5F0-1C0A-4876-BB3D-E0C23F8D5E62_1_105_c](https://github.com/yiyan023/DeafLink/assets/56096857/412cbc23-8887-4e30-8282-38eac8310ada)

- The dataset was then trained using Scikit-learn, where a dataset of 100 pictures was used to distinguish every letter -- my code contains 3 letters as a sample
