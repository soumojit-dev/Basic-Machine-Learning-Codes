# Basic Machine Learning Codes

A growing collection of **Machine Learning codes, notebooks, examples, and practice implementations**, organized from **Basics to Moderate level**.

This repository is not a single project. It is a **learning and reference repository** where different machine learning concepts, algorithms, techniques, experiments, and implementations can be added over time.

## 📚 Repository Purpose

The goal of this repository is to build a structured collection of practical ML implementations while progressing from fundamental concepts to moderately advanced techniques.

```text
Machine Learning
│
├── Basics
│   ├── Data Preparation
│   ├── Regression
│   ├── Classification
│   ├── Model Evaluation
│   └── Basic Visualization
│
└── Moderate
    ├── Cross-Validation
    ├── Hyperparameter Tuning
    ├── Feature Engineering
    ├── Feature Selection
    ├── Ensemble Methods
    ├── Dimensionality Reduction
    └── Model Comparison
```

## 🧠 Topics Covered / Planned

### 🔰 Basics

- Introduction to Machine Learning concepts
- Supervised and unsupervised learning fundamentals
- Train-test split
- Regression algorithms
- Classification algorithms
- Basic preprocessing
- Performance metrics
- Confusion matrix
- Model visualization

### 📈 Moderate

- Cross-validation
- Hyperparameter tuning
- Feature engineering
- Feature selection
- Pipelines
- Ensemble learning
- Dimensionality reduction
- Model comparison
- Handling common data-quality issues
- More systematic evaluation of ML models

> The repository will grow gradually as new algorithms and techniques are added.

## 📂 Current Contents

At present, the repository contains a Jupyter Notebook demonstrating **K-Nearest Neighbors (KNN) classification** with the Iris dataset.

### Current Notebook — KNN Classification

The notebook demonstrates:
- Loading the Iris dataset using Scikit-learn
- Stratified 80/20 train-test split
- Testing K values from 1 to 30
- 10-fold cross-validation
- Automatic selection of the best K
- KNN model training and prediction
- Accuracy score
- Classification report
- Confusion matrix
- Cross-validation performance visualization

The current notebook selects **K = 5** and reports **100% accuracy** on its held-out test set for the configured split.

## 🗂️ Suggested Repository Organization

As more examples are added, notebooks can be organized by topic:

```text
Basic-Machine-Learning-Codes/
│
├── Basics/
│   ├── Regression/
│   ├── Classification/
│   ├── Preprocessing/
│   └── Evaluation/
│
├── Moderate/
│   ├── Cross_Validation/
│   ├── Hyperparameter_Tuning/
│   ├── Feature_Engineering/
│   ├── Ensemble_Methods/
│   └── Dimensionality_Reduction/
│
├── Untitled14.ipynb
├── README.md
└── LICENSE
```

> The folder structure above represents the intended organization as the repository expands; the current repository may not yet contain all of these folders.

## 🛠️ Tools & Libraries

| Tool / Library | Use |
|---|---|
| Python | Core programming language |
| NumPy | Numerical computing |
| Pandas | Data handling and preprocessing |
| Matplotlib | Visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | ML algorithms, preprocessing and evaluation |
| Jupyter Notebook | Interactive development |
| Google Colab | Cloud-based notebook execution |

## ▶️ Getting Started

Clone the repository:

```bash
git clone https://github.com/soumojit-dev/Basic-Machine-Learning-Codes.git
cd Basic-Machine-Learning-Codes
```

Install the commonly used dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

You can also open the notebooks in **Google Colab**.

## 🎯 Learning Goals

This repository is intended to help with:

- Understanding core ML concepts through code
- Practising different ML algorithms
- Learning how to preprocess and evaluate datasets
- Comparing model performance
- Building confidence with Scikit-learn
- Progressing from beginner implementations to moderate-level ML workflows

## 🚀 Roadmap

Future additions may include implementations and practice notebooks for:

- Linear Regression
- Logistic Regression
- K-Nearest Neighbors
- Decision Trees
- Random Forest
- Support Vector Machines
- Naive Bayes
- K-Means Clustering
- Principal Component Analysis (PCA)
- Ensemble techniques
- Hyperparameter optimization
- Feature engineering workflows
- End-to-end ML examples

## 👨‍💻 Author

**Soumojit Maitra**  
B.Tech CSE (AI & ML), Brainware University

GitHub: [soumojit-dev](https://github.com/soumojit-dev)

## 📄 License

This repository is distributed under the license included in the repository.