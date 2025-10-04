#  Digits Classification using Random Forest and Stacking Classifier

This project applies **Machine Learning models** on the **Digits dataset** from sckit-learn to classify handwritten digits (0–9).  
The project demonstrates performance improvement using an **ensemble approach** — moving from a single Random Forest Classifier to a more advanced Stacking Classifier.

---

## 🚀 Key Features
- ✅ Imported the **Digits dataset** using `load_digits` from `sklearn.datasets`.  
- ✅ Split the data into **training and testing sets (80/20)** using `train_test_split`.  
- ✅ Trained and evaluated a **Random Forest Classifier** as the baseline model.  
- ✅ Built a **Stacking Classifier** combining:  
  - Logistic Regression  
  - Random Forest Classifier  
  - Support Vector Classifier (SVC)  
  - **Final Estimator:** Random Forest Classifier  
- ✅ Computed **Cross-Validation Scores** for robust model evaluation.  
- ✅ Calculated and displayed **Confusion Matrices** for both models to visualize prediction performance.  
- ✅ Achieved significant performance gain with the Stacking Classifier.  

---
## 📊 Results Summary

| 🧠 Model                     | 🧮 Cross-Val Mean Score | 🎯 Test Accuracy| ⚖️ Precision | 🔁 Recall | 📈 F1 Score |
|:-----------------------------|-------------------------:|:---------------:|:-------------:|:---------:|:------------:|
| **Random Forest Classifier** | **96.72%**               | **97.22%**      | **97.2%**     | **97.2%**  | **97.2%**   |
| **Stacking Classifier**      | **98.95%**               | **98.88%**      | **98.9%**     | **98.8%**  | **98.8%**   |

---

## ⚙️ Tech Stack
- Python  
- scikit-learn  
- NumPy  
- Matplotlib  
  

---

## 📂 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/digits-classification.git

