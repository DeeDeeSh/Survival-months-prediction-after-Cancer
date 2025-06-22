For full view of this notebook, click below

https://nbviewer.org/github/DeeDeeSh/Survival-months-prediction-after-Cancer/blob/main/Survival%20months%20after%20Cancer.ipynb

# 🧠 Predicting Remaining Time After Cancer Using Linear Regression

This project uses a synthetic dataset to model cancer survival time based on clinical features like age, tumor size, radiation dose, and gene expression levels. The goal is to demonstrate basic linear regression for medical data analysis.

---

## 📊 Dataset

A simulated dataset generated using Python.  
Each row represents a patient and includes:
- `Age`
- `Tumor_Size_cm`
- `Radiation_Dose_Gy`
- `Gene_Expression_Level`
- `Survival_Months` (target)

No real-world patient data was used.

---

## 📈 Model

- **Algorithm:** Linear Regression (from scikit-learn)
- **Goal:** Predict `Survival_Months` from clinical features
- **R² Score:** ~0.79 (shows a strong fit)

---

## 🔧 Tools Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## 📎 Key Learnings

- How to apply linear regression to healthcare-style data
- Importance of evaluating models using R²
- Plotting actual vs predicted values to visualize performance

---

## 📂 How to Run

```bash
# Clone the repo
git clone https://github.com/DeeDeeSh/linear-regression-cancer.git
cd linear-regression-cancer

# Install dependencies (optional)
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```
Made by - Devansh Sharma

Contact me-->
https://www.linkedin.com/in/devansh-sharma-02942a318/




