# Breast Cancer Prediction Using Machine Learning

A machine learning project that predicts breast cancer diagnosis using the Wisconsin Breast Cancer Diagnostic dataset.

##  What it does

This project implements two machine learning models to classify breast tissue as either **benign** or **malignant**:
- **Neural Network (MLP)**: Multi-layer perceptron with 3 layers
- **Random Forest**: Ensemble classifier with 100 decision trees

##  Dataset

- **Source**: Wisconsin Breast Cancer Diagnostic dataset
- **Features**: 30 computed morphological features (radius, texture, perimeter, area, smoothness, etc.)
- **Samples**: 569 cases (benign and malignant)
- **Location**: `dataset/data.csv`

##  Quick Start

1. **Install dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
   ```

2. **Run the notebook**:
   - Open `Code.ipynb` in Jupyter or Google Colab
   - Run all cells sequentially

##  Results

**Random Forest Performance**:
- Accuracy: 96.49%
- Precision: 96% (benign), 98% (malignant)
- Recall: 99% (benign), 93% (malignant)

**Neural Network Performance**:
- Validation Accuracy: 94.88%
- Fast convergence within 20 epochs

##  Key Features

- Data preprocessing with StandardScaler normalization
- Feature importance analysis
- Comprehensive evaluation metrics
- Visualization of results and confusion matrices
- Train-test split (80-20) for robust evaluation

##  Files

- `Code.ipynb` - Main implementation notebook
- `dataset/data.csv` - Breast cancer dataset
- `Breast_Cancer_Prediction_Thesis_Report.md` - Detailed research report

##  Research Context

This project was developed as part of a Final Year Project (FYP) comparing neural networks and ensemble methods for medical diagnosis applications.

---
