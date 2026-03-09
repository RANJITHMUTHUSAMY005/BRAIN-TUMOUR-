Brain-Tumor-MRI-Image-Classification
This project uses deep learning and transfer learning to classify MRI brain scans into glioma, meningioma, pituitary, or no tumor. A Streamlit web app enables real-time predictions, supporting early diagnosis in medical imaging.

🧠 Project Overview

This project focuses on developing a deep learning-based solution for classifying brain MRI images into multiple tumor categories. It involves building a custom CNN model from scratch and applying transfer learning techniques to enhance performance. Finally, the solution is deployed as a Streamlit web app to enable real-time predictions.

🎯 Skills Takeaway

Deep Learning

Python

TensorFlow/Keras or PyTorch

Data Preprocessing & Augmentation

Transfer Learning

Model Evaluation & Comparison

Streamlit Deployment

🌍 Domain

Medical Imaging — Image Classification

📌 Problem Statement

Brain tumors are life-threatening and require early detection for effective treatment. Manual MRI analysis is time-consuming and error-prone. This project builds an AI-powered classification system to assist radiologists by automatically predicting the tumor type from MRI scans.

💡 Real-Time Business Use Cases

AI-Assisted Medical Diagnosis → Faster, more accurate MRI tumor classification.

Early Detection & Patient Triage → Prioritize urgent cases for review.

Research & Clinical Trials → Automatically segment datasets by tumor type.

Second-Opinion AI Systems → Support telemedicine in under-resourced regions.

🔄 Project Workflow

Understand the Dataset – Analyze categories, class balance, image samples.

Data Preprocessing – Resize, normalize, and clean input MRI images.

Data Augmentation – Improve generalization with rotations, flips, zoom, etc.

Model Building

Custom CNN (from scratch).

Implement dropout & batch normalization.

Transfer Learning

Use pretrained models (ResNet50, MobileNet, EfficientNet, etc.).

Replace top layers with tumor-specific dense layers.

Model Training

Use EarlyStopping and ModelCheckpoint.

Monitor validation metrics.

Model Evaluation

Accuracy, Precision, Recall, F1-score, Confusion Matrix.

Training history plots.

Model Comparison

Custom CNN vs. Transfer Learning.

Streamlit Deployment

Upload MRI → Predict tumor type → Show confidence score.

📊 Dataset

Source: Brain Tumor MRI Multi-Class Dataset

Categories: glioma, meningioma, no_tumor, pituitary

📦 Project Deliverables

✅ Custom CNN and Transfer Learning trained models (.h5) ✅ Streamlit application for real-time classification ✅ Python scripts / Jupyter notebooks for training & evaluation ✅ Model comparison report ✅ Public GitHub repository with clean, modular, and well-commented code

🛠 Tech Stack & Tags

Tech: Python, TensorFlow, Keras, PyTorch, Streamlit Tags: Deep Learning, Image Classification, Brain MRI Analysis, Transfer Learning, Model Evaluation, Confusion Matrix, AI in Radiology
