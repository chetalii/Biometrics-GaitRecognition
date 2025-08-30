Gait Recognition using CASIA-B Dataset

This project presents a deep learning-based approach for human gait recognition using the CASIA-B dataset. The implementation involves preprocessing silhouette images, performing exploratory data analysis (EDA), and building a robust model inspired by the GaitSet architecture for accurate identity recognition based on walking patterns.

Project Overview

Human gait recognition is a biometric technique that identifies individuals based on their walking patterns. It is particularly useful in surveillance and security applications where facial recognition might not be feasible. This project utilizes the CASIA-B dataset and focuses on automating gait recognition using convolutional neural networks (CNNs).

Key Features

- 📁 Preprocessing of raw silhouette images from CASIA-B
- 📊 Exploratory Data Analysis (EDA) to understand data structure
- 🧠 Gait recognition model using deep learning (GaitSet-based architecture)
- 📈 Performance evaluation with accuracy metrics and loss curves

Dataset: CASIA-B

- Source: [CASIA Gait Database B](http://www.cbsr.ia.ac.cn/english/Gait%20Databases.asp)
- Subjects: 124 individuals
- Views: 11 camera angles
- Conditions: Normal walking, with a bag, with a coat
- Frames: Silhouette sequence images

Results:
Precision: 0.9997 
Recall: 1.00 
F1score: 0.9998 
AUC ROC: 1.00 

Tech Stack:
Python
TensorFlow / Keras
OpenCV
NumPy / Pandas / Matplotlib / Seaborn
Jupyter Notebook

Paper:Gaitpaper.docx
