# 📘 Linear Regression: Test Scores vs Hours Studied

This project demonstrates a simple **Linear Regression** model to predict students’ exam scores based on the number of study hours.  
It is a beginner-friendly Machine Learning project showing how study time influences exam results.

---

## 📂 Dataset  
- File: `score.csv`  
- Columns:  
  - `Hours` → Number of study hours  
  - `Scores` → Exam score obtained  

The dataset contains **120 rows** with a roughly linear relationship between study hours and scores.

---

## ⚙️ Tech Stack  
- **Python 3**  
- **Pandas** → Data handling  
- **NumPy** → Numerical calculations  
- **Matplotlib** → Data visualization  
- **scikit-learn** → Machine Learning (Linear Regression)  

---

## 🚀 Steps Performed  
1. Load dataset from `score.csv`.  
2. Split data into **training (80%)** and **testing (20%)**.  
3. Train a **Linear Regression** model on study hours.  
4. Predict exam scores for test data.  
5. Evaluate model using:  
   - **R² Score** → ~0.873  
   - **RMSE** → ~5.01  
6. Visualize results:  
   - Regression line on data.  
   - Actual vs Predicted scatter plot.  
   - Bar chart comparison of actual vs predicted scores.  

---

## 📊 Visualizations  

### 1. Regression Line  
Shows the fitted regression line across the dataset.  

### 2. Actual vs Predicted Scatter  
Compares real exam scores with predicted values.  

### 3. Bar Chart  
Side-by-side comparison of actual and predicted scores (sample of 20 students).  

---

## 🏆 Results  
- **R² Score:** `0.873` → Model explains ~87% of the variance in exam scores.  
- **RMSE:** `5.01` → On average, predictions are off by ~5 marks.  

---

## 📌 How to Run  
```bash
# Clone repository
git clone https://github.com/N-Jishnu/Linear-Regression-On-Test-Scores-Vs-Hours-Studied.git
cd Linear-Regression-On-Test-Scores-Vs-Hours-Studied


# Run the script
python linear_regression.py
