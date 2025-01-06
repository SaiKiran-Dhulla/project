# Advanced Techniques for Detecting Surface Defects in Industrial Settings: A Comprehensive Approach Using Deep Learning

## Overview

This project implements deep learning techniques for detecting and classifying surface defects in industrial materials. Leveraging state-of-the-art models like YOLO, VGG, and ResNet with attention mechanisms, the project demonstrates an effective approach to automate surface defect identification, improving accuracy and reducing manual inspection overhead.

# Technologies Used
   ●	Frameworks: TensorFlow
   ●	Models: CNN, Random Forest, VGG16, ResNet with CBAM, YOLOv5
   ●	Languages: Python
   ●	Tools: OpenCV, NumPy, Matplotlib, scikit-learn
# Dataset
  The project utilizes an open-source dataset from Kaggle. It contains images of industrial 
  materials with corresponding defect labels. Annotations are provided in XML format(Pascal 
  VOC).
# Setup and Installation
  Clone the repository:

git clone https://github.com/SaiKiran-Dhulla/project.git
cd project
# Set up the dataset:
Download and upload the dataset in the drive or in a local repository.
# Usage
1.	Data Understanding.ipynb file is used to understand the data, its distribution and some preprocessing required on the dataset before moving towards model building.

2.	Defect Classification.ipynb file is used to train the defect classification models - CNN + Ensemble Learning, CNN, Resnet with CBAM network, few shot classification network

3.	Defect Detection.ipynb file is used to train the defect detection model - YOLOv

4.	All the trained model weights are stored in the Trained Model Weights folder and can be used directly for inferencing the results, instead of completely training the model from scratch over the dataset.

# Key Results

1.	VGG - 82 %
2.	Resnet + CBAM - 84%
3.	YOLOv5 - 78%

# Future Scope

1.	Expand defect categories and improve dataset diversity.
2.	Combine Explainable AI technique with transfer learning approaches for better optimization.
3.	Optimize the model performance for real time applications.
# Contributing
Contributions are welcome! Please submit a pull request or create an issue if you have suggestions or bug reports.
# Acknowledgments
Special thanks to the creators of the dataset and the deep learning community for their invaluable resources.

