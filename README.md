# 🏠 Real Estate Price Prediction & Recommendation App

A **Machine Learning-powered web application** that helps users:

- 📊 Predict real estate prices  
- 📈 Analyze housing data  
- 🏢 Get apartment recommendations  

This project is built using **Python, Machine Learning, and Streamlit** to provide an interactive and user-friendly experience.

---

## 🚀 Features

### 🔹 Price Prediction
- Predict property prices based on user inputs  
- Uses trained ML model (`pipeline.pkl`)  

### 🔹 Data Analysis
- Provides visual insights using data visualization  
- Helps understand trends in the housing market  

### 🔹 Apartment Recommendation
- Recommends similar apartments using similarity models  
- Uses cosine similarity (`cosine_sim.pkl`)  

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python  
- **Machine Learning:** Scikit-learn  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  

---

## 📂 Project Structure

```
Real-Estate-App/
│── datasets/
│   ├── data_viz1.csv
│   ├── cosine_sim1.pkl
│   ├── cosine_sim2.pkl
│   ├── cosine_sim3.pkl
│   ├── feature_text.pkl
│   ├── location_distance.pkl
│
│── pages/
│   ├── 1_Price_Predictor.py
│   ├── 2_Analysis_App.py
│   ├── 3_Recommmend_Appartments.py
│
│── Home.py
│── pipeline.pkl
│── df.pkl
│── latlong_scraper.py
│── requirements.txt
```

---

## ⚙️ How to Run

```bash
git clone https://github.com/12Abhinagar/Real-Estate-App.git
cd Real-Estate-App

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

streamlit run Home.py
```

---

## 👨‍💻 Author

**Abhishek Nagar**  
- B.Tech CSE (2023–2027)  
- Strong interest in Data Science & Problem Solving  
- Solved 700+ DSA problems  

---
