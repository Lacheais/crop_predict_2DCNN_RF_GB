# crop_predict_2DCNN_RF_GB
# Crop Yield Prediction Using CNN and Ensemble Learning

This repository contains the code and architecture for my undergraduate thesis project, which predicts crop yield per plant based on environmental factors using artificial intelligence. The system uses a 2D Convolutional Neural Network (CNN) combined with ensemble models such as Random Forest and Gradient Boosting, tuned with Optuna for performance.

# Overview
- **Author:** Lacheais
- **Year:** 2025

This work aims to improve the accuracy of yield prediction for bell pepper crops by modeling the relationship between environmental inputs across plant growth stages and the resulting yield.

# Features

- Input features: soil type, moisture, luminosity, duration per growth stage
- Output: yield per plant (0–10)
- 2D CNN model with 3 growth stages as input tensor
- Ensemble stack: CNN + Random Forest + Gradient Boosting
- Weighted Mean Squared Error loss to improve high-yield predictions
- Flask API for integration with Unity frontend


#  Project Structure

crop_predict_2DCNN_RF_GB/
├── gitignore/ # Git ignored files
├── LICENSE/ # MIT
├── README.md # Project description
├── pred1 (2).py #Python File
├── pred1.ipynb #Jupyter Notebook File
├── requirements.txt # Requirements for program execution
