# CompanyProfitPredictor
```markdown
# 📈 Company Profit Prediction using Linear Regression

This project demonstrates how to predict company profits using linear regression, achieving **R² = 0.9958** with a clean and interpretable model — **without overfitting**.

---

## 📂 Project Structure

- `CompanyProfitPrediction.ipynb` — Jupyter Notebook with all steps
- `1000_Companies.csv` — Dataset used
- `README.md` — You’re here!
---

## 📌 Highlights

- ✅ Outlier removal using **IQR method**
- ✅ Feature encoding without `drop_first`
- ✅ Feature scaling using **StandardScaler**
- ✅ Comparison of **Linear**, **Ridge**, and **Lasso** regression
- ✅ Visualization and residual analysis
- ✅ Regularization to confirm model robustness
- ✅ Verified against overfitting using:
  - Train/Test R² scores
  - Residual plots
  - Lasso feature elimination

---

## 🚀 Technologies Used

- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook
- SciPy

---

## 🧪 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/profit-prediction-linear-regression.git
```

2. Install dependencies

3. Launch the notebook:
```bash
jupyter notebook CompanyProfitPrediction.ipynb
```

---

## 📊 Results

- **R² Score (Test Set):** `0.9958`


---

## 🧠 Inspiration

Inspired by a curiosity: *Can simple regression models still work this well if the data is clean and the pipeline is strong?*  
The answer: **Yes.** ✅

---

## 📬 Feedback

Found this useful or have ideas to improve it?  
Feel free to open issues or contribute via pull requests.

---
