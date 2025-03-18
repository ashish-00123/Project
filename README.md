🌿 Plant Disease Detection
🚀 Overview

This project is a Deep Learning-based Plant Disease Detection system that classifies plant leaves into different disease categories using image classification techniques. It utilizes CNN architectures and transfer learning to achieve high accuracy.
🔥 Key Features

    Fusion Model: Combines Xception and DenseNet121 architectures for better classification.
    Image Augmentation: Uses Keras ImageDataGenerator to improve model generalization.
    Transfer Learning: Leverages pre-trained models (Xception, DenseNet121) for faster and more accurate predictions.
    Model Ensembling: Averages predictions from multiple models to enhance accuracy.

🏗️ Tech Stack

    Python 🐍
    TensorFlow / Keras for deep learning
    OpenCV, Matplotlib, Seaborn for image processing & visualization
    Pandas, NumPy for data handling
    Google Colab / Jupyter Notebook for development

📊 Methodology

    Data Preprocessing:
        Read & analyze plant dataset (train.csv, test.csv).
        Resize & normalize images.
        Perform data augmentation (rotation, flipping, zooming).
    Model Selection & Training:
        Implement Xception & DenseNet121 CNN models.
        Train models separately & ensemble predictions.
        Use categorical cross-entropy loss function.
    Evaluation & Prediction:
        Visualize loss & accuracy curves.
        Predict plant diseases on test images.
        Generate submission.csv with predicted probabilities.
