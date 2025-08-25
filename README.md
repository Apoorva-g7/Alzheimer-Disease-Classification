# 🧠 Alzheimer’s Disease Classification from MRI Scans

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

## 📂 Dataset
This project uses the **[Alzheimer MRI Dataset](https://www.kaggle.com/datasets/yasserhessein/dataset-alzheimer)** available on Kaggle.  

- The dataset contains **Train** and **Test** folders with thousands of MRI images.  
- To run this project locally:
  1. Download the dataset from Kaggle.
  2. Extract it and place it inside a `data/` directory:  

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

# Create a virtual environment (recommended)
python -m venv venv

source venv/bin/activate
# on Linux/Mac

venv\Scripts\activate
# on Windows

# Install dependencies
pip install -r requirements.txt
