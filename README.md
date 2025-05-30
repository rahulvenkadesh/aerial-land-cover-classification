# aerial-land-cover-classification
Deep learning-based aerial image land cover classification using Tailored UNET and satellite imagery.

# Aerial Land Cover Classification using Tailored U-Net

This project demonstrates semantic segmentation of aerial images for land cover classification using a custom-designed U-Net model built with TensorFlow/Keras.

## 🧠 Model Architecture

- Tailored U-Net with:
  - Encoder: Multiple Conv2D + BatchNorm + Dropout layers
  - Decoder: Conv2DTranspose + skip connections from encoder
  - Output layer: Softmax for multi-class classification
- Input image size: **256x256x3**
- Optimizer: Adam
- Loss: Categorical Crossentropy

## 📁 Files
- `Aerial_Land_Classification.ipynb`: The main Jupyter Notebook
- `README.md`: Project documentation
- `requirements.txt`: Python package dependencies

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/aerial-land-cover-classification.git
   cd aerial-land-cover-classification
