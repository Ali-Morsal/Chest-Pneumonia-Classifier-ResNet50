# 🫁 Chest Pneumonia Classifier

## ✨ Features
- **Accuracy**
  - Achieved Validation Accuracy = 97.43%
  - F1-Score = 0.9824 
  - [Download Checkpoint](https://1024terabox.com/s/1PlRygrpVPPbeZnarK4yrTQ)

---

## 📌 Project Overview
Pneumonia is a lung infection that can be life-threatening if not diagnosed early. This project leverages **deep learning** to classify chest X-rays into:
- **Normal**
- **Pneumonia**

The model is trained on publicly available dataset ([Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)).

---

## ⚙️ Features
- Data preprocessing and augmentation for robust training  
- Convolutional Neural Network (CNN) architecture  
- Training and evaluation with accuracy, loss, and confusion matrix  
- Visualization of predictions  
- Easy-to-use notebook for reproducibility  

---

## 🫀 Lung Segmentation (Preprocessing Step)

Before training the classifier, a **lung segmentation** step ([Link](https://github.com/Ali-Morsal/Lung-Segmentation-using-DenseUNet)) was applied to the chest X-ray images.  
The goal of this preprocessing step is to make the **lungs more visible** by removing irrelevant background and focusing only on the lung region.  

Benefits of segmentation:
- Reduces noise and irrelevant features (e.g., ribs, labels, background)  
- Improves model accuracy and generalization  
- Ensures the CNN focuses on actual lung patterns related to pneumonia  

This preprocessing ensures that the classifier learns **relevant medical features** and not unnecessary artifacts in the images.

---

