# Handwritten Text Recognition Model

This repository contains an AI model designed to recognize and predict text from images of handwritten words. The model combines 5 Convolutional Neural Networks (CNNs) and 3 Recurrent Neural Networks (RNNs) for robust accuracy, with Connectionist Temporal Classification (CTC) loss for optimized sequence prediction.

## Dataset

The model is trained on the [IAM Handwriting Word Database](https://www.kaggle.com/datasets/iam-database) from Kaggle, which provides a diverse set of handwriting samples essential for model accuracy and generalization.

## Model Architecture

- **CNN Layers:** 5 layers used for feature extraction from handwritten text images  
- **RNN Layers:** 3 layers to learn sequential dependencies within the extracted features  
- **Loss Function:** Connectionist Temporal Classification (CTC) loss for effective alignment and text sequence prediction  

## Performance

- **Character Accuracy:** 89.4124%  
- **Word Accuracy:** 70.8018%  

This model demonstrates a powerful approach to handwriting recognition, making it suitable for applications in document digitization, accessibility solutions, and automated text processing.

## Components

- **`OCR_model.ipynb`** - The primary notebook for model training and experimentation.
- **`Predictor.ipynb`** - A notebook demonstrating how to use the trained model to extract text from new images.
- **`ocr_model_saved.keras`** - The saved, trained model for deployment.
- **`Documentation.pdf`** - Detailed documentation on the project, including model architecture and training process.
- **`test_image.png`** - A sample image used for testing the model's performance.
