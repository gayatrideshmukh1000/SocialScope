# 🌐 SocialScope AI  
### Decoding Digital Behavior & Well-being  

---

## 📌 Project Overview
SocialScope AI is a Machine Learning-based dashboard that analyzes social media usage patterns and their impact on user well-being.  

The system processes datasets related to sleep, stress levels, and social media activity to generate insights and predictions. It can predict:
- 📱 Social media platform preference  
- 🧠 Health impact based on usage  

The project is built using Streamlit and provides an interactive interface for data analysis and real-time predictions.

---

## 🚀 Features
- 📊 Data quality checks (missing values, duplicates)  
- ⚙️ Data cleaning and feature engineering  
- 🔗 Correlation and statistical analysis  
- 🤖 Machine Learning models:
  - Random Forest (Platform Prediction)  
  - Gradient Boosting (Health Prediction)  
- 📈 Interactive visualizations using Plotly  
- 🧠 Real-time predictions  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Plotly  
- Streamlit  

---

## 📂 Project Files
- `app.py` → Main Streamlit application  
- `sleep_dataset.xlsm` → Health dataset  
- `social_media.xlsm` → Social media dataset  
- `requirements.txt` → Dependencies  

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/SocialScope-AI.git
cd SocialScope-AI
2. Install dependencies
pip install -r requirements.txt
3. Run the app
streamlit run app.py
📊 Results & Insights
Identifies patterns between social media usage and health
Shows correlation between screen time and sleep/stress
Predicts user behavior using ML models
Provides interactive visual insights
