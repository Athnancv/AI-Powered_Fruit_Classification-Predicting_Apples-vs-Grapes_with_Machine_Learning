# AI-Powered_Fruit_Classification-Predicting_Apples-vs-Grapes_with_Machine_Learning
An end-to-end machine learning project that classifies apples and grapes based on their physical and visual characteristics. This project demonstrates how data preprocessing, feature extraction, and model optimization can be combined to achieve high-accuracy fruit classification — showcasing the power of machine learning in agricultural 
---

# 🍎 Apple vs Grapes Classification using Machine Learning

---

## 📌 Project Overview  
The goal of this project is to **predict whether a fruit is an Apple or a Grape** based on a structured dataset.  
This notebook covers every major step in a **supervised learning workflow** — including **data cleaning**, **exploratory data analysis (EDA)**, **model development**, **hyperparameter tuning**, and **model evaluation**.

---

## 🎯 Objectives  
- Preprocess fruit dataset for modeling  
- Explore the structure and relationship between fruit features  
- Train and compare **Decision Tree** vs **K-Nearest Neighbors (KNN)** classifiers  
- Use **GridSearchCV** for hyperparameter tuning  
- Evaluate and visualize model performance  

---

## 🗂️ Dataset  

**Features included:**  
- Diameter  
- Weight  
- Color Score  
- Label (Apple / Grape)  

---

## 🔍 Key Highlights of the Project  

### ✅ Data Loading & Preprocessing  
- Imported the dataset with structured numeric and categorical features  
- Checked for missing values, duplicates, and inconsistencies using `.info()` and `.describe()`  
- Applied **Label Encoding** to convert categorical fruit types into numeric form  
- Split the data into **80% training** and **20% testing** sets using `train_test_split()`  

---

### 📊 Exploratory Data Analysis (EDA)  
- Visualized fruit characteristics using:  
  - Histograms  
  - Boxplots  
  - Pairplots  
- Checked for class separability and feature correlations  
- Used statistical functions to summarize **mean**, **median**, and **variance** across fruit types  

---

### 🤖 Model Building  
- Trained a **Decision Tree Classifier** as the baseline model  
- Improved performance using **K-Nearest Neighbors (KNN)** — leveraging distance-based classification for better accuracy  

---

### 🔧 Hyperparameter Tuning  
Used **GridSearchCV** to identify optimal parameters for both models:  
- `max_depth`, `criterion` for Decision Tree  
- `n_neighbors`, `weights` for KNN  

✅ Achieved better accuracy and reduced overfitting through systematic tuning  

---

### 📈 Model Evaluation & Comparison  
Evaluated both models using:  
- ✅ **Accuracy Score**  
- 📊 **Confusion Matrix**  
- 📋 **Classification Report (Precision, Recall, F1-Score)**  

**Result:**  
KNN slightly outperformed the Decision Tree, showing improved classification accuracy and better generalization performance.  

---

## 🛠 Tools & Technologies Used  
- 🐍 **Python**  
- 🧮 **NumPy**, **Pandas** — Data handling & preprocessing  
- 📊 **Matplotlib**, **Seaborn** — Visualization  
- 🤖 **Scikit-learn** — ML modeling, evaluation, and tuning  
- ⚙️ **GridSearchCV** — Hyperparameter optimization  
- 📓 **Jupyter Notebook** — Step-by-step workflow and visualization  

---

## 💡 Conclusion  
This project demonstrates how even simple structured datasets can be used to build **accurate fruit classification systems**.  
Through effective **data preprocessing**, **visualization**, and **model optimization**, the notebook showcases the power of **machine learning in agricultural and visual analytics**.  

---

## 🔮 Future Enhancements  
- 📈 Add **feature importance** plots for model interpretability  
- 🧠 Implement **cross-validation** and ensemble methods like **Random Forest**  
- 🍊 Extend the dataset to include more fruit types (multi-class prediction)  
- 🌐 Deploy the trained model using **Streamlit** or **Flask**
