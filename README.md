# pcos-image-classification
Deep Learning project for classifying Polycystic Ovary Syndrome (PCOS) images using CNN and transfer learning CNN. Includes data preprocessing, model training, evaluation, and visualization of results.
# PCOS Image Classification

## Project Overview
This project uses **Deep Learning (CNN)** to classify images for **Polycystic Ovary Syndrome (PCOS)**. The goal is to build a model that accurately identifies PCOS from medical images.

## Dataset
- Images sourced from(https://raw.githubusercontent.com/Sowmiya-1999/Sowmiya/refs/heads/main/PCOS%20dataset.zip) 
- Number of images: [e.g., 1000]  
- Classes: PCOS / Non-PCOS  

## Approach / Methods
### Data Preprocessing
- Image resizing, normalization, and augmentation (rotation, flipping, zoom)

### Model Architecture
- CNN base model   
- Fine-tuning top layers for PCOS classification  
- Activation: ReLU (hidden), Softmax (output)

### Training Details
- Optimizer: Adam  
- Loss: Categorical Cross-Entropy  
- Epochs: [e.g., 50]  
- Batch size: [e.g., 32]

## Results
- Training Accuracy: ~98%  
- Validation Accuracy: ~95%  
- Confusion matrix and sample predictions included in notebook


