# 🦴 AI-Based Multilabel Knee Injury Detection using VGG16

## 📌 Overview
This project presents a deep learning-based approach for multilabel knee injury detection using MRI scans. The model is built using the VGG16 architecture with transfer learning to classify three common knee conditions:

- Abnormal
- ACL Tear
- Meniscus Tear

The model processes MRI images from axial, sagittal, and coronal planes and predicts multiple labels simultaneously.

---

## 🚀 Features

- VGG16 Transfer Learning
- Multilabel Classification
- MRI Image Processing
- Data Augmentation
- Performance Evaluation using Accuracy, Precision, Recall, F1-Score and AUC-ROC
- Confusion Matrix Visualization
- Model Saving and Loading

---

## 📂 Dataset

This project uses the **MRNet Knee MRI Dataset**.

> The dataset is not included in this repository due to its large size.

---

## 🛠 Technologies Used

- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Results

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC
- Confusion Matrix

Project outputs include:

- Class Distribution
- Model Architecture
- Confusion Matrices
- AUC vs F1 Comparison

---

## 📁 Project Structure

```
VGG16/
│
├── code/
├── configs/
├── output/
├── individual_images/
├── VGG16_Multilabel_Knee_Injury.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.
2. Download the MRNet dataset.
3. Update the dataset path.
4. Install dependencies.
5. Run the notebook.

---

## 📈 Future Improvements

- Vision Transformer (ViT)
- ResNet50 Comparison
- Explainable AI (Grad-CAM)
- Web Deployment using Streamlit

---

## 👨‍💻 Author

**Ayush Yati**

B.Tech Computer Science Engineering

GitHub: https://github.com/Ayushyati25
