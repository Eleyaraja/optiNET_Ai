# 👁️ OptiNet: AI-Powered Retinal Disease Detection

OptiNet is an AI-based retinal disease classification system designed to detect 9 different eye conditions from fundus images — including those captured using smartphones. Our goal is to make early screening affordable and accessible, particularly in underserved communities.

---

## 🚀 Project Goals

- Detect 9 common retinal diseases using deep learning
- Enable affordable early screening with mobile-acquired images
- Provide real-time classification support in a lightweight pipeline

---

## 🧠 Diseases Detected

- Myopia  
- Central Serous Chorioretinopathy  
- Glaucoma  
- Disc Edema  
- Diabetic Retinopathy  
- Retinitis Pigmentosa  
- Macular Scar  
- Retinal Detachment  
- Healthy

---

## 🏗️ Tech Stack

- **Framework:** TensorFlow / Keras  
- **Models Used:** EfficientNetV2B3, ResNet50, InceptionV3  
- **Attention Modules:** SE (Squeeze-and-Excitation), CBAM  
- **Augmentation:** Smartphone simulation (blur, noise, glare)  
- **Training Platform:** Google Colab + GPU (memory optimized)  
- **Dataset:** Custom retinal dataset with 13,500+ images

---

## 🧪 Features

- Multi-backbone deep learning architecture  
- Handles image noise, blur, and real-world quality degradation  
- Imbalanced dataset handling and augmentation  
- Training checkpoints, resume support  
- Flask integration (optional) for web demo

---

## 🔁 Inference Flow

1. Capture or upload a retinal fundus image  
2. Preprocess with custom filters  
3. Predict disease class using trained model  
4. Display disease name, description & medical suggestions

---

## 🗃️ Dataset Info

The dataset is organized into folders per class (9 categories), sourced and preprocessed to simulate mobile imaging conditions. Stored in Google Drive for easy Colab access.

---

## 📦 How to Run

Clone the repo and open the notebook in Google Colab:

```bash
git clone https://github.com/yourusername/optiNet-retina-ai.git
