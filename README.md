# Paper-Recyclability-Detection using YOLOv8

This project focuses on detecting the recyclability of paper using the Yolov8 object detection model. The model classifies papers into two categories: recyclable and non-recyclable, based on the recycling standard of the National Solid Waste Management Commission, and only includes paper with stains, tape, braille, and waterproof papers as non-recyclable.

# Features

•	Real-time Detection: Uses the OpenCV library to integrate webcam functionality for real-time detection.

•	Custom Dataset: Trained on a dataset of 20,883 images, including augmented and null images.

•	Strong Performance: Achieved excellent evaluation metrics, such as mAP (Mean Average Precision).

# Dataset

The dataset used to train the model was created collaboratively by me and my team member. It was available publicly for testing, and for more information, visit [Paper Recyclability Detection](https://universe.roboflow.com/serge-de-guzman-and-christian-gomez/paper-recyclability-detection).

# Training environment

• Python 3.11.9

• Ultralytics 8.3.19 which were downgraded to 8.0.196 as a requirement for Roboflow deployment

• Roboflow 

• OpenCV

• Torch 2.5.0 and Tensorflow (For usage of CUDA)

• Cuda 11.8

• GPU: NVIDIA GeForce GTX 1650

# Performance Metrics

Below are the key performance metrics for the model on the validation dataset. Detailed images of the confusion matrix, mAP curves, and other evaluation results are provided in the runs/detect/train folder.

•	mAP@50: 95.6%

•	mAP@50-95: 92.6%

•	Precision: 91.4%

•	Recall: 92.1%









https://github.com/user-attachments/assets/f67e4adc-b40a-48f5-8ac7-0484dd908773

