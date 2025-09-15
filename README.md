# 🔬 Breast Cancer Prediction using Machine Learning

A machine learning project that predicts whether a breast tumor is **malignant** or **benign** using the Breast Cancer Wisconsin (Diagnostic) dataset.  
This project demonstrates **data preprocessing, exploratory data analysis (EDA), model building, and evaluation** of multiple machine learning algorithms.

---

## 📊 Dataset
- **Samples**: 569  
- **Features**: 30 numerical features describing cell nuclei characteristics  
- **Target**:  
  - `0` → Malignant  
  - `1` → Benign  

---

## 🛠️ Tech Stack
- Python 🐍  
- NumPy, Pandas → Data handling  
- Matplotlib, Seaborn → Visualization  
- Scikit-learn → Machine Learning  

---

## ⚙️ Workflow
1. Load and explore dataset  
2. Preprocess data (cleaning, scaling, splitting)  
3. Perform exploratory data analysis (EDA)  
4. Train models:
   - Logistic Regression  
   - Random Forest  
5. Evaluate models using accuracy 

---

## 📈 Results
- Best performing model: **LogisticRegression**
- Achieved accuracy: **95%**  
- Insights:
  - Certain features (like `mean radius`, `mean concavity`) strongly influence predictions.  
  - Ensemble models performed better than individual models.  

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Feature selection/engineering  
- Trying deep learning models (ANNs, CNNs)  
- Deployment as a **Flask/Streamlit web app**

---


