# Splicing-Factor-Analysis-R
Exploratory Data Analysis and Predictive Modeling with Synthetic Splicing Dataset using R
# Splicing Factor Analysis using R

## 📌 Overview
This project explores the relationship between splicing factors and splicing event expression using a synthetic gene expression dataset. The goal is to identify key predictors influencing splicing events through exploratory data analysis and statistical modeling.

---

## 📊 Dataset
- Synthetic dataset with **100 subjects**
- Variables:
  - SplicingFactor1
  - SplicingFactor2
  - SplicingFactor3
  - SplicingEvent (response variable)

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis (EDA)
- Assessed **distribution, central tendency, and variability**
- Generated **correlation matrix** to examine relationships between variables
- Visualized data using:
  - Histograms
  - Boxplots
  - Scatterplots with regression lines

### Key Findings:
- **Factor1**: Moderate positive correlation with splicing event (r ≈ 0.52)  
- **Factor2**: Strong negative correlation (r ≈ -0.63)  
- **Factor3**: No meaningful correlation  

---

### 2. Statistical Modeling
- Built a **Multiple Linear Regression Model**:
- Model Performance:  **R² = 0.63**
- Adjusted R² = 0.61

### Interpretation:
- **SplicingFactor1**: Significant positive predictor (p < 0.001)  
- **SplicingFactor2**: Significant negative predictor (p < 0.001)  
- **SplicingFactor3**: Not statistically significant  

---

### 3. Model Evaluation
- Evaluated predictive performance using:
- **RMSE = 2.27**
- **MAE = 1.71**
- **MSE = 5.13**

- The model demonstrates **moderate predictive accuracy** and captures overall trends in the data.

---

## 📈 Tools & Technologies
- **R**
- Libraries used:
- ggplot2
- dplyr
- stats (for regression modeling)

---

## ✅ Key Takeaways
- SplicingFactor1 and SplicingFactor2 are the primary drivers of splicing event expression.
- SplicingFactor3 does not significantly contribute to prediction.
- Linear regression is effective in capturing relationships in this dataset.

---

## 🚀 Future Improvements
- Apply **regularized regression (Lasso/Ridge)** for improved model performance  
- Explore **non-linear models**  
- Use **real-world biological datasets** for validation  
- Increase sample size for stronger statistical power  


