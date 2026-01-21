
# Diabetes Progression Prediction using ANN 🧠💉

This project implements an **Artificial Neural Network (ANN)** to model the progression of diabetes
using the **Diabetes dataset from the sklearn library**.  
The project is developed as part of a **Deep Learning module end assignment**.

---

## 🎯 Objective
To understand how clinical features influence diabetes progression and to build an ANN-based
regression model for prediction.

---

## 📊 Dataset
- Source: sklearn.datasets.load_diabetes
- Samples: 442
- Features: 10
- Target: Diabetes progression score

---

## ⚙️ Workflow

### 1. Data Loading & Preprocessing
- Loaded dataset from sklearn
- Verified absence of missing values
- Normalized features using StandardScaler

### 2. Exploratory Data Analysis (EDA)
- Target variable distribution analysis
- Feature correlation heatmap visualization

### 3. ANN Model
- Input layer with feature-based neurons
- Hidden layers with ReLU activation
- Output layer for regression

### 4. Training
- Train-test split (80:20)
- Optimizer: Adam
- Loss: Mean Squared Error

### 5. Evaluation
- Mean Squared Error (MSE)
- R² Score

### 6. Model Improvement
- Increased depth and number of neurons
- Improved prediction accuracy

---

## 📈 Results

| Model Version | MSE | R² |
|--------------|------|----|
| Initial Model | 3018.73 | 0.43 |
| Improved Model | 2824.36 | 0.47 |

---

## 📁 Project Structure

```
├── Diabetes_ANN_Assignment.ipynb
├── README.md
```

---

## ▶️ How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
jupyter notebook Diabetes_ANN_Assignment.ipynb
```

---

## 🧠 Conclusion
The ANN model successfully captures non-linear relationships in diabetes data.  
Performance improvement after tuning confirms the effectiveness of deeper architectures.

---

## 👤 Author
**Suroora Fathima**

---

## 📜 License
Educational use only.
