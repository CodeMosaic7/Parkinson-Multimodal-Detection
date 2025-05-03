# Multimodal Parkinson's Disease Detection Model

This repository contains a deep learning-based multimodal framework for the early detection and classification of Parkinson's Disease (PD). The model integrates multiple data types — such as voice recordings, handwriting/drawing patterns, and facial expressions — to improve diagnostic accuracy using advanced neural network architectures.

## 🧠 Overview

Parkinson's Disease is a progressive neurodegenerative disorder. Early diagnosis is critical for managing symptoms and improving quality of life. Our multimodal approach leverages the complementary strengths of various biosignals to detect PD more reliably than unimodal systems.

## 🚀 Features

- Multimodal inputs: voice, handwriting/drawing, and facial video/image analysis
- Preprocessing pipelines for each modality
- Feature extraction using CNNs, RNNs, and transformers (depending on modality)
- Late fusion architecture for combining modality-specific features
- Binary classification: Parkinson's vs. Healthy
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score, AUC

## 🧾 Modalities Used

1. **Voice Analysis**  
   - Acoustic features (MFCCs, jitter, shimmer)
   - Processed via CNN/RNN-based models

2. **Handwriting/Drawing Analysis**  
   - Spiral drawings and handwriting samples
   - Image preprocessing and CNN-based classification

     Working on.
3. **Facial Analysis**  
   - Micro-expressions and movement features
   - Extracted from video frames using facial landmark detection and CNNs



