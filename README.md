# 📩 SMS Spam Classifier  
A machine learning project that classifies SMS/Email messages as **Spam** or **Not Spam**, built using **Python, Scikit-Learn, NLP**, and deployed as a web app using **Streamlit**.

---

## 🚀 Project Overview  
This project demonstrates a complete end-to-end ML workflow — from **data preprocessing** to **deployment** — to build a spam detection system using Natural Language Processing.

---

### **1. Data Cleaning**
- Removed duplicates and null values  
- Converted text to lowercase  
- Removed special characters and irrelevant patterns  

### **2. Exploratory Data Analysis (EDA)**
- Visualized class distribution (spam vs ham)  
- WordClouds for spam and ham messages  
- Analyzed message lengths and patterns  

### **3. Data Preprocessing**
- Tokenization  
- Stopwords removal  
- Stemming using `PorterStemmer`  
- TF-IDF vectorization  

### **4. Model Building**
Trained multiple models such as:
- Naïve Bayes  
- Logistic Regression  
- SVM  
- Random Forest  

Used TF-IDF vectors as features.

### **5. Evaluation**
Evaluated models using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

### **6. Improvement**
- Tuned hyperparameters  
- Compared multiple ML models  
- Selected the best model based on **precision for spam detection**

---

## 🌐 7. Deployment Using Streamlit  
The final working classifier was deployed as a simple web app inside the **venv** environment.

### **Run the Streamlit App**
```bash
streamlit run streamlit_app.py
