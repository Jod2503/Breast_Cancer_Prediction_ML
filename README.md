# 🩺 Breast Cancer Prediction using Machine Learning

A machine learning project that predicts whether a breast tumor is **Benign** or **Malignant** using the Breast Cancer Wisconsin dataset. This project demonstrates the complete machine learning pipeline, including data preprocessing, exploratory data analysis, model training, hyperparameter tuning, and model evaluation.

---

## 📌 Project Overview

Breast cancer is one of the most common cancers worldwide. Early diagnosis can significantly improve treatment outcomes. This project uses machine learning classification algorithms to predict whether a tumor is malignant or benign based on various medical features.

---

## 📂 Dataset

**Dataset:** `data.csv`

The dataset contains features extracted from digitized images of breast mass cell nuclei, including:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

**Target Variable**

- `M` → Malignant
- `B` → Benign

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🚀 Machine Learning Workflow

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Label Encoding
- Train-Test Split
- Model Training
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation

---

## 🤖 Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (if included)

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation Score

---

## 📁 Project Structure

```text
Breast-Cancer-Prediction/
│
├── breast-cancer-prediction-using-machine-learning.ipynb
├── data.csv
├── README.md
└── .gitignore
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction.git
```

Move into the project directory:

```bash
cd Breast-Cancer-Prediction
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
breast-cancer-prediction-using-machine-learning.ipynb
```

---

## 📈 Results

The notebook compares multiple machine learning models and evaluates their performance using various classification metrics. Hyperparameter tuning is applied to improve prediction accuracy.

---

## 🔮 Future Improvements

- Add XGBoost and LightGBM
- Deploy using Streamlit
- Save trained models with Joblib
- Add feature importance visualization
- Build an interactive prediction interface

---

## 👨‍💻 Author

**Joditya**

B.Tech (Instrumentation & Control Engineering)

Interested in Machine Learning, AI, and Data Science.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
