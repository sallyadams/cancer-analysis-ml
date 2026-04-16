# cancer-analysis-ml
Breast cancer data analysis and prediction using Python, EDA, and machine learning.
## 📊 Breast Cancer Prediction & Analysis

### 🔍 Overview
End-to-end analysis of a breast cancer dataset to identify key predictors of malignancy and build a simple classification model.

### 🧹 Data Preparation
- Dropped `id`
- Imputed missing values (mean)
- Encoded `diagnosis` (1 = malignant, 0 = benign)

### 📊 EDA
- Correlation heatmap
- Boxplot comparison (radius_mean vs diagnosis)
- Key features: radius, perimeter, area, concavity

### 🤖 Model
- Logistic Regression (train/test split 80/20)
- Achieves high accuracy on test set

### 📈 Key Insights
- Malignant tumors have higher size-related features
- Several features are strongly correlated (multicollinearity)
- Tumor size is a strong indicator of cancer

### 🛠 Tech
Python, Pandas, Seaborn, Matplotlib, scikit-learn

### ▶️ How to run
1. Open `notebook/cancer_analysis.ipynb`
2. Run all cells

### 👩‍💻 Author
Salamat Adams — Data Analyst | AI & Data Storytelling

images/heatmap.png
images/boxplot.png
