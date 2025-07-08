# 🧠 Enhanced Disease Classification with HybridCNNViT and SMOTE

This repository contains the official code for my master’s thesis project:  
🎓 *Enhanced Disease Classification with HybridCNNViT model and Synthetic Oversampling (SMOTE)*  
📘 Course: Statistical Methods for Data Science  
🏫 University: Lund University

---

## 📌 Abstract

Early and accurate classification of skin diseases plays a crucial role in improving diagnostic efficiency and patient outcomes. This project introduces **HybridCNNViT**, a deep learning architecture that combines **Convolutional Neural Networks (CNNs)** and **Vision Transformers (ViTs)** to capture both local texture and global structure in skin lesion images.

To address class imbalance—where rare but critical conditions are underrepresented—we apply **SMOTE (Synthetic Minority Oversampling Technique)** during data preprocessing. Key model enhancements include:
- Attention mechanisms for region focus
- Regularization to prevent overfitting
- Dynamic learning rate scheduling
- Data augmentation techniques

The model was evaluated on a dermatology dataset and achieved:
- 🎯 Test precision: **87.77%**
- 🧮 Weighted F1 Score: **0.8747**
- 🧠 Methods Used:[XGBoost / CNN / LSTM / PCA / SMOTE]
- 🧰 Libraries Used: pandas, numpy, scikit-learn, matplotlib, seaborn, torch, torchvision

---

