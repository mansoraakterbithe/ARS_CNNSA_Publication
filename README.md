# ARS-CNNSA
Arsenic And Skin Diseases Classification.
# 🧠 Skin Disease Classification using Deep Learning (ARS-CNNSA)

## 📌 Overview
Skin diseases such as **arsenic-induced lesions, melanoma, psoriasis, and eczema** often share visually similar characteristics, making accurate diagnosis challenging. This project presents a **deep learning-based classification system** designed to distinguish arsenic-related skin conditions from other common dermatological diseases.

The proposed model, **ARS-CNNSA (Attention-based Convolutional Neural Network Skin Analyzer)**, demonstrates superior performance compared to several well-known pre-trained architectures.

---

## 🚀 Key Features
- 🔍 Accurate classification of multiple skin diseases
- ⚡ Lightweight architecture with fewer hyperparameters
- 🧠 Integrated **self-attention mechanism** for improved feature extraction
- 📊 Outperforms traditional transfer learning models
- 🌍 Useful for regions with high arsenic exposure

---

## 🧪 Dataset
- Custom dataset consisting of images from:
  - Arsenic-induced lesions
  - Melanoma
  - Psoriasis
  - Eczema
- Preprocessing includes:
  - Image resizing
  - Normalization
  - Data augmentation

---

## 🏗️ Models Evaluated

| Model            | Accuracy |
|------------------|----------|
| VGG16            | 85%      |
| MobileNetV2      | ~80%     |
| InceptionV3      | 82%      |
| **ARS-CNNSA (Proposed)** | **91%** |

---

## 📈 Performance Metrics
- ✅ **Accuracy:** 91%
- 🎯 **F1-Score:** 90%
- 📉 Reduced overfitting using attention mechanisms
- ⚙️ Efficient training with fewer hyperparameters

---

## 🧠 Model Architecture (ARS-CNNSA)
The proposed model includes:
- Convolutional (Conv2D) layers for feature extraction
- Self-attention mechanism for capturing global dependencies
- Fully connected layers for classification

---

## 🛠️ Tech Stack
- Python 🐍
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn

---

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/skin-disease-classification.git
cd skin-disease-classification
```
---
## Dataset Link
https://www.kaggle.com/datasets/sayedhossainjobayer/skin-diseases-dataset



