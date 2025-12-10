# Exploring the Impact of Multilayer Perceptron Architecture on Breast Cancer Classification

This project investigates how changes in the depth and width of a Multilayer Perceptron (MLP) influence classification performance on the Breast Cancer Wisconsin Diagnostic Dataset. The goal is to help students and practitioners understand how model architecture affects accuracy, generalisation, and clinical usefulness in medical machine-learning tasks.

The repository contains:
- The full Jupyter Notebook with code, experiments, and visualisations  
- A written tutorial/report explaining the concepts behind MLPs  
- Figures used in the report  
- Preprocessing, feature selection, PCA implementation, and model evaluation steps  

---

## 📌 Project Motivation

Breast cancer early detection is essential for improving patient outcomes. Machine-learning models, particularly neural networks, can support clinicians by identifying patterns in tumour measurements that differentiate benign from malignant cases. This project shows how MLP design choices impact performance and reliability.

---

## 📊 Dataset Information

The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, containing:

- **569 samples**
- **30 numerical input features**
- **Binary target class**: Benign (0) or Malignant (1)

Features describe tumour characteristics such as radius, area, concavity, smoothness, and texture.  
Data is included via scikit-learn or CSV.

---

## 🧠 Methods Overview

The project evaluates four MLP architectures:

- **MLP (1×16)** – one hidden layer, 16 neurons  
- **MLP (1×64)** – one hidden layer, 64 neurons  
- **MLP (2×16,16)** – two hidden layers, 16 neurons each  
- **MLP (2×64,64)** – two hidden layers, 64 neurons each  

Additional steps:

- Standardisation of all numerical features  
- Feature selection using Random Forest importance  
- Optional PCA reducing features to 6 principal components  
- Performance measured using:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion matrix

---

## 📈 Key Figures Included

The tutorial includes four recommended images:

1. **Feature Importance Bar Chart**  
2. **MLP Architecture Accuracy Comparison**  
3. **Confusion Matrix of Best Model**  
4. **Scatter Plot of Relevant Tumour Features**

These appear in both the report and notebook.

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/breast-cancer-mlp-architecture.git
cd breast-cancer-mlp-architecture



.
├── README.md
├── LICENSE
├── Breast_Cancer_Classification_with_MLP.ipynb
├── tutorial.pdf
├── figures/
│   ├── feature_importance.png
│   ├── accuracy_comparison.png
│   ├── confusion_matrix.png
│   └── feature_scatter.png
└── data/
    └── breast_cancer.csv (optional if using sklearn loader)
