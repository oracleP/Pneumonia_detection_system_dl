# Pneumonia_detection_system_dl
This project aims to develop an intelligent Pneumonia Detection System using Machine Learning (ML) and Deep Learning (DL) techniques to identify pneumonia from chest X-ray images. Pneumonia is a potentially life-threatening infection that primarily affects the lungs. Early and accurate detection is crucial for timely treatment, especially in under-resourced medical environments.

Our system leverages computer vision models trained on labeled chest X-ray datasets to classify images into Pneumonia and Normal categories.
Technologies Used
Machine Learning:
Feature Extraction from images using traditional techniques (e.g., HOG, SIFT).

Classifiers: Support Vector Machine (SVM), Random Forest, k-NN.

Deep Learning:
Convolutional Neural Networks (CNNs) for end-to-end image classification.

Transfer Learning with pre-trained models like:

ResNet50

VGG16

MobileNetV2

📁 Dataset
The dataset used in this project is the Chest X-Ray Images (Pneumonia) dataset available from Kaggle. It contains:

Normal chest X-ray images.

Pneumonia-affected chest X-ray images (both bacterial and viral).

⚙️ Features
Real-time prediction on new chest X-ray images.

Visualization of model performance with accuracy/loss curves and confusion matrix.

Comparative analysis between ML and DL models.

High accuracy with fine-tuned CNNs.

📈 Evaluation Metrics
Accuracy

Precision, Recall, F1-Score

Confusion Matrix

ROC-AUC Curve

🚀 Future Improvements
Integration with web/mobile interface for easy deployment.

Multi-class classification (e.g., bacterial vs viral pneumonia).

Grad-CAM for visual explanation of model predictions.
