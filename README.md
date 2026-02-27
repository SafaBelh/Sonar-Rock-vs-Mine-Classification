# 🌊 Sonar Rock vs. Mine Classification 🚀

![Banner](images/banner.png)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Mv4s36_jMpitXrTupEVJeuSZNPKwC7Qu)

## 📌 Project Overview

This project implements a **Binary Classification Machine Learning Model** to analyze sonar signals and determine whether an underwater object is a:
- 🪨 **Rock (R)**  
- 💣 **Mine (M)**

By utilizing **Logistic Regression** on sonar frequency data, this model serves as a practical example of applying machine learning to signal processing scenarios.

---

## 📊 Dataset Information

The model is trained on a dataset containing sonar signal measurements:
- **Features:** 60 numerical input features representing energy measurements across different frequency bands.
- **Target Variable:** 1 column indicating the class (`R` for Rock, `M` for Mine).
- **Distribution:** The dataset is well-balanced to ensure reliable model training.

---

## ⚙️ Technologies & Libraries

- **Python 🐍**
- **NumPy** (`numpy`) - For numerical operations and data reshaping.
- **Pandas** (`pandas`) - For data loading and manipulation.
- **Scikit-Learn** (`scikit-learn`) - For the Logistic Regression algorithm, data splitting, and evaluation metrics.
- **Matplotlib** (`matplotlib`) - Optional, for data visualization.

---

## 🚀 Getting Started

Follow these steps to run the project locally on your machine.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SafaBelh/Sonar-Rock-vs-Mine-Classification.git
cd Sonar-Rock-vs-Mine-Classification
```

### 2️⃣ Install Dependencies

It is recommended to use a virtual environment. Install the required packages using:

```bash
pip install -r requirements.txt
```

### 3️⃣ Execute the Model

Run the main script to train the model and see predictions:

```bash
python sonar_classification.py
```

---

## 📈 Model Performance

The Logistic Regression model was evaluated using a 90/10 train-test split, preserving class balance via stratification.

| Metric | Accuracy |
| :--- | :---: |
| **Training Accuracy** | 83% |
| **Test Accuracy** | 76% |

---

## 🎓 Educational Notes & Concepts

### Why Logistic Regression?
Logistic Regression is ideal for binary classification tasks. It uses a **Sigmoid Function** to map linear mathematical outputs into probabilities between 0 and 1.
- **Probability ≥ 0.5** → Classified as Mine (M)
- **Probability < 0.5** → Classified as Rock (R)

### Why use `stratify=Y` in Train-Test Split?
The `stratify` parameter ensures that the proportion of Rocks to Mines remains consistent across both the training and testing datasets, preventing skewed learning.

### Why use `random_state`?
Setting a `random_state` (e.g., `1`) ensures that the random split of data is exactly the same every time the code is run, allowing for **reproducible results**.

---

## 👩‍💻 Author

**Safa Belhouche**  

© 2026 Safa Belhouche — All Rights Reserved