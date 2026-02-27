# 🌊 SONAR ROCK VS MINE CLASSIFICATION 🚀

![Banner](images/banner.png)

## 📌 Project Overview

This project builds a **Binary Classification Model** to detect whether a sonar signal represents:

- 🪨 Rock (R)  
- 💣 Mine (M)

We use **Logistic Regression** to classify underwater objects based on sonar frequency data.

---

## 🧠 Machine Learning Concepts Covered

- Binary Classification
- Logistic Regression
- Sigmoid Function
- Feature Scaling
- Train/Test Split
- Overfitting vs Underfitting
- Confusion Matrix

---

## 📊 Dataset Information

- 60 numerical input features  
- 1 target variable (Rock or Mine)  
- Balanced dataset

---

## ⚙️ Technologies Used

- Python 🐍  
- NumPy  
- Pandas  
- Scikit-Learn  
- Matplotlib (optional)

---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Sonar-Rock-vs-Mine-Classification.git
cd Sonar-Rock-vs-Mine-Classification
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Script

```bash
python sonar_classification.py
```

---

## 📈 Model Performance

| Metric            | Value |
| ----------------- | ----- |
| Training Accuracy | XX%   |
| Test Accuracy     | XX%   |

---

## 🎓 Educational Notes

### Why Logistic Regression?

Logistic Regression uses a **Sigmoid Function** to convert linear outputs into probabilities between 0 and 1.

- Probability ≥ 0.5 → Mine  
- Probability < 0.5 → Rock

---

### Why stratify=Y?

Preserves class balance during train/test split.

---

### Why random_state?

Ensures reproducibility of results.

---

## 👩‍💻 Author

**Safa Belhouche**  

© 2026 Safa Belhouche — All Rights Reserved