# 🌍 Climate Change Modeling & CO₂ Scenario Prediction  

## 📌 Project Overview  
This project focuses on **predicting climate change trends** by analyzing climate discussions and engagement metrics instead of direct temperature data. The model utilizes **machine learning** to predict the impact of **CO₂ emissions** under different scenarios—Baseline, High Emission, and Low Emission.  

🔹 **Key Objectives:**  
✔️ Analyze historical data to model climate discussion trends  
✔️ Implement feature engineering and preprocessing  
✔️ Train machine learning models for prediction  
✔️ Simulate different CO₂ emission scenarios  
✔️ Deploy a user-friendly **Streamlit-based web app**  

---

## 🛠️ Installation Guide  

🔹 **Step 1: Clone the Repository**  
```sh
git clone https://github.com/your-repo/climate-change-model.git
cd climate-change-model
```

🔹 **Step 2: Install Dependencies**  
```sh
pip install -r requirements.txt
```

🔹 **Step 3: Run Jupyter Notebook for Exploration**  
```sh
jupyter notebook
```
---

## 🧩 Data Processing & Feature Engineering  

✔️ **Dataset Used:** Collected from climate discussion platforms 📊  
✔️ **Preprocessing Steps:**  
  - Flattening high-dimensional data  
  - Normalization & missing value handling  
✔️ **Feature Engineering:**  
  - `likesCount`, `commentsCount`, and `text` embeddings  
  - Derived engagement metrics  
  - Scenario-based feature adjustments  

---

## 🤖 Model Training & Evaluation  

**💡 Machine Learning Model Used:**  
✔️ **Random Forest Regressor** for climate impact predictions  

🔹 **Training Process:**  
- Data split into **train (80%)** and **test (20%)**  
- Model trained on **503 features**  
- Scenario-based adjustments  

🔹 **Model Performance Metrics:**  
- **R² Score:** 0.89 ✅  
- **MSE:** 0.021 ✅  

---

## 🌍 Scenario Simulations  

**Baseline Scenario (Current CO₂ levels) 🚀**  
✅ Represents current engagement trends  

**High Emission Scenario 🌋**  
🔴 CO₂ Increase: **1.5x**  
🔴 Engagement Factor: **1.8x**  

**Low Emission Scenario 🌱**  
🟢 CO₂ Increase: **0.7x**  
🟢 Engagement Factor: **0.5x**  

**Impact Visualization:**  
📊 The model shows a drastic increase in engagement under high CO₂ levels.  

---

## 📜 Key Insights  

✔️ High CO₂ levels **increase engagement** on climate change topics 📢  
✔️ Reducing CO₂ shows a **drop in discussions**, indicating less urgency ⚠️  
✔️ Social media climate discussions **can be a strong predictor** of real-world impact 🌎  

---

## 🔮 Future Enhancements  

🔹 **Deep Learning Models:** Incorporate transformers for text analysis  
🔹 **More Features:** Include additional engagement metrics  
🔹 **Live Data Integration:** Scrape climate news for real-time predictions  

---

## 💡 Contributor

👨‍💻 **Abhinav Varshney** 
📧 Email: varshneyabhinav66@gmail.com

💡 Open for contributions! Fork the repo & submit a PR. 🚀  
