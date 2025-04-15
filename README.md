# 🏥 Statistical Modeling of Healthcare Cost and Health Risk

This project applies **regression analysis and generalized linear models** (GLMs)  
to explore the relationship between individual characteristics (e.g., age, BMI, smoking)  
and two key outcomes:

1. **Medical charges** (continuous outcome)
2. **Health risk status** (binary outcome)

---

## 📊 Overview

The project consists of two tasks:

### Task 1 – Linear Regression on Medical Charges
- Estimates how age, BMI, smoking status, gender, and region impact total medical charges
- Uses OLS estimation, model diagnostics, and variable selection techniques
- Includes residual analysis and adjusted R² for model performance

### Task 2 – Logistic Regression on Health Risk
- Predicts binary health risk status using patient indicators such as cholesterol, glucose, and blood pressure
- Fits binomial GLM with logit link
- Performs likelihood ratio tests and AIC comparison
- Evaluates classification accuracy using confusion matrix

---

## 🗃️ Files

- `Health_Charges_Regression.Rmd` – Code in R Markdown format
- `sample_charges.csv` – Simulated dataset used for modeling
- `Analys` - Full analysis for the original data

---

## 📁 Simulated Data Disclaimer

> 📌 The dataset used in this project is **simulated** and created for demonstration purposes only.  
> It replicates the structure of a proprietary teaching dataset and does **not** represent any real individuals.

---

## 🧰 Tools Used

- R, RMarkdown
- `lm()`, `glm()`, AIC, residual plots
- Simulated healthcare data

---

## 👤 Author

Jiyu Zhang  
MSc in Financial Mathematics  
BSc in Actuarial Science
*Originally developed as part of my Master's coursework at Heriot-Watt University*
