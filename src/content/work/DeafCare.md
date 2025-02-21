---
title: TeleDeaf Care
publishDate: "2024-11-15"
img: /assets/DeafCare.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  We developed an AI-powered telehealth platform designed to assist individuals with hearing impairments through real-time sign language recognition and healthcare accessibility solutions.
tags:
  - AI
  - Telehealth
  - Deep Learning
---

# Introduction

TeleDeaf Care is an AI-driven telehealth platform aimed at improving healthcare accessibility for the deaf community in Australia. This project integrates real-time sign language recognition to facilitate seamless communication between patients and healthcare providers.

# Project Overview

## Technologies Used

+ Frameworks:  PyTorch, Mediapipe, Flask

+ Programming Languages: Python

+ Computer Vision Tools: OpenCV, Transformers, Sign Language Recognition Models

# Key Features

1. Real-Time Sign Language Recognition

+ Achieved 94% accuracy using CNN1D + Transformer architecture.

+ Processed 543 landmark points via Mediapipe and Z-score normalization.

2. Optimized Model Performance

+ Implemented K-fold cross-validation, Focal Loss, and Data Augmentation.

+ Enhanced model generalization for diverse user inputs.

3. User-Friendly Deployment

+ Designed an accessible Streamlit UI for non-technical users.

+ Ensured seamless Flask-based API integration for real-world applications.

4. Performance Evaluation

+ Measured effectiveness via Confusion Matrix, F1-score, Precision, and Recall.

+ Iteratively improved model based on real-world feedback.

# Challenges and Solutions

+ Sign Language Complexity: Utilized Transformer models to improve gesture understanding.

+ Ensuring High Model Accuracy: Applied data augmentation techniques to enhance training efficiency.

+ User Accessibility: Designed an inclusive UI with multilingual support for diverse users.

# Conclusion

TeleDeaf Care represents a step forward in AI-driven healthcare accessibility. By combining Deep Learning, NLP, and Computer Vision, this project bridges communication gaps and enhances medical support for the deaf community. Future enhancements include speech-to-text conversion and expanded language support.