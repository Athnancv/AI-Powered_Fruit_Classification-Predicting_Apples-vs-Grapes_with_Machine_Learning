#🍊 **Orange vs Grapes Classification using Machine Learning**

## 📌 Project Overview
The goal of this project is to predict whether a fruit is an **Orange or a Grape** based on a structured dataset.  
This notebook includes all major steps in a supervised machine learning workflow:
- Data cleaning
- Exploratory Data Analysis (EDA)
- Model training
- Hyperparameter tuning
- Model evaluation

---

## 🎯 Objectives
- Preprocess fruit dataset for ML
- Analyze relationships between fruit features
- Train & compare **Decision Tree vs KNN**
- Optimize models using **GridSearchCV**
- Evaluate performance using classification metrics

---

## 🗂️ Dataset Features
- **Diameter**
- **Weight**
- **Color Score**
- **Label** → Orange / Grape

---

## 🔍 Key Highlights

### ✅ Data Loading & Preprocessing
- Loaded structured CSV data
- Checked missing values & duplicates
- Applied Label Encoding
- Split data: **80% train / 20% test**

### 📊 Exploratory Data Analysis
Visualizations include:
- Histograms
- Boxplots
- Pairplots  
Also:
- Checked feature correlations
- Calculated mean, median, variance

---

## 🤖 Model Building
- **Decision Tree Classifier** (Baseline)
- **K-Nearest Neighbors (KNN)** — improved accuracy using distance-based metrics

---

## 🔧 Hyperparameter Tuning (GridSearchCV)
**Decision Tree**
- `max_depth`
- `criterion`

**KNN**
- `n_neighbors`
- `weights`

✔️ Reduced overfitting and improved performance

---

## 📈 Model Evaluation
Used:
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1)

**Result:**  
KNN slightly outperformed Decision Tree with better accuracy and generalization.

---

## 🛠 Tools & Technologies
- Python 🐍
- NumPy, Pandas — Data processing
- Matplotlib, Seaborn — Visualization
- Scikit-learn — Modeling & Tuning
- GridSearchCV — Optimization
- Jupyter Notebook — Implementation

---

## 💡 Conclusion
This project demonstrates how even simple structured data can build accurate fruit classification models.  
With preprocessing, visualization, and tuning — ML proves useful for agricultural analytics.

---

## 🔮 Future Enhancements
- Feature importance visualization
- Cross-validation & ensembles (Random Forest)
- Multi-class fruit prediction
- Deploy using Streamlit or Flask
```
