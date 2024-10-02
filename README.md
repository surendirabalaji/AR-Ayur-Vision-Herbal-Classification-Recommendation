Project Overview
AyurVision is a comprehensive system designed to classify and recommend Indian herbal plants using image classification and phytochemical analysis. This project integrates machine learning techniques, computer vision, and augmented reality to identify medicinal plants and provide relevant recommendations for similar plants. The model uses a Convolutional Neural Network (CNN) to classify plant images, with the ONNX format used for compatibility across frameworks.

Objectives
Develop an efficient and user-friendly system for identifying and recommending Indian herbal plants.
Utilize deep learning and computer vision techniques to classify plant species based on their image features.
Create a recommendation system that suggests similar plants based on shared characteristics.
Enhance the accessibility of Ayurvedic plant knowledge for experts and enthusiasts.
System Architecture
The project consists of three main modules:

Image Classification Model: Utilizes CNN for accurate identification of herbal plants.
Unity Detection Model: Employs Unity and ONNX to integrate the image classification into an augmented reality environment.
Recommendation Model: Uses a similarity matrix based on phytochemical profiles to recommend herbal plants.
Features
1. Image Classification
The image classification model is based on a CNN that learns from a dataset of herbal plant images. Data augmentation techniques like rotation, scaling, and flipping were used to improve the model’s accuracy and generalization capabilities.

2. Recommendation System
The recommendation model uses a database of phytochemical profiles to identify and suggest plants with similar therapeutic uses. It analyzes the identified plant and uses a similarity metric to provide alternative herbal plants.

3. ONNX Model Conversion
The image classification model is converted to ONNX format for compatibility and integration with Unity. This allows for augmented reality applications where the identified plant can be viewed in real time with additional information displayed.

Project Implementation
Dataset Description
Image Dataset: Consists of images for 30 different herbal plant species, collected from public datasets like Kaggle.
Plant Profile Dataset: Data scraped from the IMPATT database, containing details on 4,095 plant species, 1,095 therapeutic uses, and 17,965 phytochemicals.
Tools & Technologies
Deep Learning Framework: TensorFlow, for CNN implementation.
Programming Languages: Python (for model development), C# (for Unity integration).
Unity: For augmented reality implementation.
ONNX: For model conversion and interoperability.
System Requirements
Hardware Requirements: Laptop with a minimum of 12GB RAM and a 256GB SSD.
Software Requirements: Python, TensorFlow, Unity, C#.
Results
Image Classification
SVM Model: Achieved an accuracy of 16% on the validation set.
CNN Model without Data Augmentation: Achieved a training accuracy of 100% and validation accuracy of 80%.
CNN Model with Data Augmentation: Further improved validation accuracy to 90%.
Recommendations
The recommendation system uses a similarity matrix to recommend plants based on shared phytochemical properties.
