# Brain Tumor Segmentation using Tailored U-Net (BRATS 2020)

This project implements a deep learning-based brain tumor segmentation model using a customized U-Net architecture trained on the BRATS 2020 dataset.

## 🧠 Dataset

- **BRATS 2020** (Brain Tumor Segmentation Challenge)
- Multi-modal MRI scans: T1, T1c, T2, FLAIR
- Task: Segment tumor subregions — edema, enhancing tumor, necrotic core
- Download from: [Kaggle - BRATS 2020](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation)

## 🧬 Model

- **Tailored U-Net** architecture:
  - Encoder: Conv2D + BatchNormalization + Dropout
  - Decoder: Conv2DTranspose + skip connections
  - Final Activation: Softmax
- Input: 256x256 MRI slices
- Loss: Categorical Crossentropy
- Optimizer: Adam

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/brats2020-unet-segmentation.git
   cd brats2020-unet-segmentation
