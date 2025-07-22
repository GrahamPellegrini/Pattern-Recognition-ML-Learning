<h1 align="center">Pattern Recognition & Machine Learning Projects</h1>

<p align="center">
  <a href="https://www.um.edu.mt/courses/studyunit/CCE2502">
    <img src="https://img.shields.io/badge/University%20of%20Malta-CCE2502-blue?style=for-the-badge" alt="CCE2502">
  </a>
  <a href="https://github.com/GrahamPellegrini/Pattern-Recognition-ML-Learning">
    <img src="https://img.shields.io/badge/Topic-Pattern%20Recognition%20%26%20ML-green?style=for-the-badge" alt="Pattern Recognition">
  </a>
  <a href="https://www.um.edu.mt/profile/gianlucavalentino">
    <img src="https://img.shields.io/badge/Lecturer-Dr.%20Gianluca%20Valentino-lightgrey?style=for-the-badge" alt="Supervisor">
  </a>
</p>

---

## 📚 Overview

This repository contains implementations and experiments conducted as part of the [CCE2502](https://www.um.edu.mt/courses/studyunit/CCE2502) unit, **Pattern Recognition and Machine Learning** at the University of Malta. The work spans two comprehensive assignments:

- **Assignment I** – Classification using synthetic datasets and kNN benchmarking
- **Assignment II** – Logistic regression from scratch using gradient descent and regularisation

Each assignment is structured as a separate notebook, with annotated explanations and visual outputs.

> 🧾 Both assignments were implemented and completed during Semester II, 2023/2024.

---

## 🧪 Assignment I: Classification & Benchmarking

### 🔧 Tasks & Highlights

- **Task 1**: 
  - Generate and visualise synthetic datasets with `make_circles` and `make_blobs`
  - Inspect feature distribution, means, and standard deviations

- **Task 2**:
  - Implement custom `Shuffle_SplitDataset()` and `ClassificationMetrics()` functions
  - Evaluate metrics: **Accuracy**, **Recall**, **Precision**, **F1-score**

- **Task 3**:
  - Apply **k-Nearest Neighbours (k-NN)** algorithm using `sklearn`
  - Tune `k` for optimal **accuracy** and **F1-score**
  - Train/test/validation pipeline

- **Task 4**:
  - Compare **brute-force** vs **kd-tree** methods for inference timing
  - Scale experiments to datasets of size `10^2` to `2.5x10^5`
  - Empirical validation of complexity analysis for `kNN`

📄 See `assignment_I.pdf` for full code, metrics, and plotted results.

---

## 📈 Assignment II: Logistic Regression (Scratch Implementation)

### 🧩 Core Components

- Implemented from scratch using NumPy:
  - Logistic loss function (categorical cross-entropy)
  - Prediction via sigmoid activation
  - Accuracy computation
  - Regularised gradient descent

- **Visualisation & Validation**:
  - Decision boundary plotted against training data
  - Convergence plots of training and validation loss

- **Dataset Analysis**:
  - Compare linearly separable vs non-separable datasets
  - Polynomial feature expansion (degree 2 to 4)
  - Evaluation of regularisation impact

- **Bonus**: Comparison with `sklearn.MLPClassifier` on advanced datasets

📄 See `CCE2502_Assignment_II.pdf` for all implementation details and analysis.

---

## 🧠 Key Learnings

- Manual implementation of logistic regression solidified understanding of:
  - Gradient descent dynamics
  - Regularisation and weight decay
  - Decision boundary intuition

- Reinforced ability to:
  - Generate, visualise, and split datasets
  - Evaluate classifier performance using custom metrics
  - Scale and benchmark ML algorithms (e.g., kNN)

---

## 🚀 How to Run

1. Clone this repository
2. Open the `.ipynb` notebooks in Jupyter or VS Code
3. Install any missing dependencies:
```bash
pip install matplotlib numpy scikit-learn
```
4. Run each notebook sequentially (e.g., `Assignment I`, `Assignment II`)

---

## 📌 Tags

```
logistic-regression, knn, ml-from-scratch, classification, benchmarking, sklearn, pattern-recognition, cce2502, university-of-malta
```

---

## 👨‍💻 Author

**Graham Pellegrini**  
University of Malta – Department of Computer Engineering  
GitHub: [@GrahamPellegrini](https://github.com/GrahamPellegrini)

📄 Report Files:
- [`Assignment_I.pdf`](assignment_I.pdf)
- [`Assignment_II.pdf`](CCE2502_Assignment_II.pdf)
