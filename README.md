# Basic Machine Learning Codes

A beginner-friendly machine learning notebook demonstrating **K-Nearest Neighbors (KNN) classification** using the classic **Iris dataset**.

## 📌 Project Overview

This repository demonstrates a practical machine learning workflow:
- Loading the Iris dataset
- Splitting data into training and testing sets
- Evaluating K values from 1 to 30
- Selecting the best K using 10-fold cross-validation
- Training a KNN classifier
- Evaluating predictions with accuracy and a classification report
- Visualizing model performance and the confusion matrix

## 🤖 Algorithm: K-Nearest Neighbors

KNN is a supervised learning algorithm that classifies a data point based on the classes of its nearest training examples.

In this notebook, K values from **1 to 30** are evaluated using **10-fold cross-validation**, and the K value with the highest mean validation accuracy is selected automatically.

## 🌸 Dataset

The project uses the built-in **Iris dataset** from Scikit-learn.

Features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Target classes:
- Setosa
- Versicolor
- Virginica

## 🔬 Workflow

```text
Iris Dataset
     ↓
Train / Test Split
     ↓
Evaluate K = 1 ... 30
     ↓
10-Fold Cross-Validation
     ↓
Select Best K
     ↓
Train KNN Model
     ↓
Predict Test Data
     ↓
Evaluate Performance
     ↓
Visualize Results
```

## 📊 Evaluation

The notebook uses:
- **Accuracy Score**
- **Classification Report** — precision, recall and F1-score
- **Confusion Matrix**
- **Cross-validation accuracy plot** for different K values

The current notebook output selects **K = 5** and reports **100% test accuracy** on the held-out test set.

> Note: Results are specific to the current train/test split and notebook configuration (`random_state=42`, stratified 80/20 split).

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Confusion matrix visualization |
| Scikit-learn | Dataset, KNN, cross-validation and metrics |
| Jupyter Notebook / Google Colab | Development environment |

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/soumojit-dev/Basic-Machine-Learning-Codes.git
cd Basic-Machine-Learning-Codes
```

### 2. Install dependencies

```bash
pip install numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook
```

Then open **`Untitled14.ipynb`**.

You can also upload the notebook directly to **Google Colab**.

## 📁 Repository Structure

```text
Basic-Machine-Learning-Codes/
│
├── Untitled14.ipynb   # KNN classification notebook
├── README.md          # Project documentation
└── LICENSE            # Repository license
```

## 🎯 Learning Objectives

This project builds foundational skills in:
- Supervised learning
- Classification
- KNN
- Cross-validation
- Hyperparameter selection
- Model evaluation
- Confusion matrices
- Basic machine learning visualization

## 🚀 Future Improvements

- Add feature scaling and compare results
- Compare KNN with Logistic Regression, Decision Trees and SVM
- Add exploratory data analysis visualizations
- Experiment with different train/test configurations
- Organize additional machine learning algorithms into separate notebooks

## 👨‍💻 Author

**Soumojit Maitra**  
B.Tech CSE (AI & ML), Brainware University

GitHub: [soumojit-dev](https://github.com/soumojit-dev)

## 📄 License

This project is distributed under the license included in this repository.