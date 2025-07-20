# 🧠 Remote Worker Mental Health Prediction using Machine Learning

This project applies supervised machine learning to predict and classify the **mental health status** of remote employees (Good, Moderate, Poor) based on various work-related, personal, and behavioral features. The dataset used comes from Kaggle and includes anonymized responses from remote professionals across different countries and roles.

---

## 📁 Dataset

**Source**: [Mental Health of Remote Workers — Kaggle](https://www.kaggle.com/datasets/abhishekjaiswal4896/mental-health-of-remote-workers)

**Features Used:**

- Age  
- Gender  
- Country  
- Job Role  
- Experience Years  
- Work Mode  
- Hours Worked Per Week  
- Productivity Score  
- Burnout Score  
- Sleep Hours Per Day  
- Exercise Frequency  
- Work-Life Balance Rating  
- Remote Setup Satisfaction  
- Internet Issues Frequency  
- Team Communication Effectiveness  
- Mental Health Status (Target)

---

## 🧪 Objectives

- Predict the **mental health condition** of remote workers as either:
  - Good
  - Moderate
  - Poor

- Explore how work environment, lifestyle, and job satisfaction relate to mental well-being.

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for model building & evaluation
- **SMOTE / Resampling** for handling class imbalance
- **Kaggle Kernels** for execution

---

## 📊 ML Pipeline

1. Data Cleaning & Preprocessing  
2. Feature Selection & Encoding  
3. Data Balancing  
4. Model Training (Logistic Regression, Decision Trees)  
5. Evaluation (Accuracy, Precision, Recall, F1 Score)  

---

## 🔍 Model Performance

The models were evaluated using accuracy and classification metrics. Due to **class imbalance**, additional balancing techniques were tested to improve results on underrepresented classes.

---

## ✅ Results

- Accuracy improved slightly after handling class imbalance.
- Majority class ("Good") had better precision & recall.
- Minority classes ("Poor", "Moderate") remain harder to classify — future work could involve:
  - Collecting more balanced data
  - Using advanced classifiers like XGBoost or ensemble methods
  - Exploring NLP for text-based feedback (if added)

---

## 📌 Conclusion

This project highlights the importance of mental health monitoring for remote teams and demonstrates how machine learning can assist in early detection using non-invasive survey-based data.

---

## 💡 Future Improvements

- Deploy a dashboard using **Streamlit**
- Add feature importance & explainability (e.g., SHAP values)
- Integrate real-time predictions based on survey input

---

## 🤝 Contributions

Contributions, ideas, and feedback are welcome! Feel free to open issues or submit pull requests.

---
