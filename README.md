# Alzheimer-Disease-Classification
Deep learning project for classifying Alzheimer’s Disease stages from MRI scans using CNNs, transfer learning, data augmentation and imbalance handling techniques.
## 📌 Project Overview
This project focuses on classifying different stages of Alzheimer’s Disease from MRI scans using Deep Learning.  
The goal is to support early detection and diagnosis by leveraging CNN-based architectures and transfer learning.

---

## 🚀 Key Highlights
- **Data Challenges**:
  - MRI brain scans require preserving anatomical structure → used **intensity-based augmentations** instead of geometric ones.
  - Severe **class imbalance** tackled with **class-weighted loss functions**, **oversampling**, and multiple architectures.
  - Risk of **overfitting** addressed with **transfer learning**, **dropout**, **regularization**, and **early stopping**.
  - **Hardware constraints** handled by resizing images, optimizing batch sizes, and GPU-efficient preprocessing.

- **Approach**:
  - Preprocessing with intensity normalization.
  - Augmentations: brightness, contrast, noise injection, elastic deformations.
  - Models: Custom CNNs & Transfer Learning (ResNet, VGG, etc.).
  - Evaluation using accuracy, precision, recall, F1-score.

---

## 📂 Files
- `alzheimer_disease_classification.ipynb` → Main notebook with preprocessing, training, evaluation.
- `requirements.txt` (optional) → Dependencies for reproducibility.

---

## 📊 Results
- Improved model robustness with augmentation.
- Balanced learning achieved through class-weighted training.
- Achieved strong validation accuracy while mitigating overfitting.

---

## ⚡ Future Work
- Extend to 3D CNNs for volumetric MRI data.
- Explore attention-based architectures for medical imaging.

---

## 🛠️ Tech Stack
- **Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib**
- **GPU-accelerated training**

---

## 📌 How to Run
```bash
git clone https://github.com/<your-username>/Alzheimer-Disease-Classification.git
cd Alzheimer-Disease-Classification
jupyter notebook alzheimer_disease_classification.ipynb
