# 🏠 House Price Prediction

A Machine Learning model that predicts house prices using **Linear Regression**. Built from scratch to understand the fundamentals of supervised learning.

---

## 🎯 What It Does

```
Input:  MedInc=8.3, AveRooms=6.9, HouseAge=41, Population=322
Output: Predicted Price → $450,000
```

---

## 📊 Results

| Metric | Value |
|--------|-------|
| R² Score (4 features) | 0.486 |
| R² Score (all features) | 0.576 |
| RMSE | 0.746 (×$100K) |
| Training Samples | 16,512 |
| Test Samples | 4,128 |

**Key Finding:** Adding more features improved R² by +0.090, proving that Feature Engineering directly impacts model performance.

---

## 🏗️ What I Built

```
California Housing Dataset (20,640 samples)
      ↓
Exploratory Data Analysis (scatter plots, correlations)
      ↓
Feature Selection (MedInc had highest correlation: 0.68)
      ↓
Train/Test Split (80/20)
      ↓
Linear Regression Training
      ↓
Evaluation (R², RMSE)
      ↓
Feature Engineering → Improved Results
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| ML Model | scikit-learn LinearRegression |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Language | Python 3.11 |

---

## 📦 Installation

```bash
git clonehttps://github.com/RashaAlorabi/house-price-prediction.git
cd house-price-prediction

python3 -m venv env
source env/bin/activate

pip install -r requirements.txt
```

---

## 🚀 Usage

```bash
jupyter notebook house_price_prediction.ipynb
```

---

## 🔑 Key Learnings

- **Feature Correlation** — MedInc (income) had the strongest correlation (0.68) with price
- **Feature Engineering** — Creating new features like `RoomsPerPerson` improved results
- **StandardScaler** — Normalizing features improved model stability
- **R² Score** — Model explains 57.6% of price variance; remaining 42.4% = irreducible error

---

## 📁 Project Structure

```
house-price-prediction/
├── house_price_prediction.ipynb   # Main notebook
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📋 Requirements

```txt
scikit-learn
numpy
pandas
matplotlib
jupyter
```

---

## 🚧 Future Improvements

- [ ] Try Random Forest for better accuracy
- [ ] Add interactive price predictor
- [ ] Deploy as REST API with FastAPI

---

## 👤 Author

**Rasha** — Senior Software Engineer → AI Solutions Engineer
