# 🏏 IPL Cricket Data Analytics

## 📌 Overview
This project performs comprehensive data analytics on the Indian Premier League (IPL) dataset spanning **18 seasons (2008–2025)**.  
It analyzes match-level and ball-by-ball data to uncover patterns, trends, and insights using statistical methods, visualization, and predictive modeling.

---

## 📄 Abstract
The project processes structured IPL datasets including matches, deliveries, players, and seasons.  
It applies **EDA, hypothesis testing, and regression models** to identify:
- Batting vs chasing advantages  
- Scoring trends over seasons  
- Key factors influencing match outcomes  
- Prediction of win margins  

---

## 🎯 Objectives
- Analyze IPL match and delivery data  
- Identify key factors affecting match outcomes  
- Perform data visualization (EDA dashboards, heatmaps)  
- Conduct statistical hypothesis testing  
- Build regression models for predictions  
- Study scoring evolution over seasons  

---

## 🚀 Features
- Data loading from multiple CSV datasets  
- Data cleaning and preprocessing  
- Feature engineering (run_diff, boundaries, high scoring matches)  
- 9-panel EDA dashboard visualization  
- Statistical tests:
  - T-Test  
  - Chi-Square  
  - Mann-Whitney U  
  - Shapiro-Wilk  
- Regression models:
  - Simple Linear Regression  
  - Multiple Linear Regression  
- Season-wise trend analysis  

---

## 📊 Dataset
The dataset consists of:

- `matches.csv` → Match-level data (1158 rows)  
- `deliveries.csv` → Ball-by-ball data (134,190 rows)  
- `players.csv` → Player information (580 rows)  
- `seasons.csv` → Season summaries (18 seasons)  

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔧 Implementation

### Data Preprocessing
- Handled missing values  
- Converted date formats  
- Encoded categorical variables  
- Standardized team names  

### Feature Engineering
- `run_diff` → Difference between innings scores  
- `high_scoring` → Matches with score ≥ 180  
- Boundary detection (four, six)  

---

## 📈 Analysis & Results
- Strong correlation between innings scores (**r = 0.80**)  
- Batting-first teams score ~19 runs more (statistically significant)  
- High-scoring matches favor batting team  
- Regression Model Performance:
  - Simple Model → R² = 0.656  
  - Multiple Model → R² = 0.747  

---

## 📊 Visualizations
- 9-panel EDA dashboard  
- Run-rate and wicket probability graphs  
- Correlation heatmap  
- Regression plots  
- Season-wise trends (runs, sixes, scoring)  

---

## 🌍 Real-World Applications
- Team strategy optimization  
- Player performance analysis  
- Fantasy cricket insights  
- Broadcasting analytics  
- Data science learning project  

---

## 📚 Learning Outcomes
- End-to-end data analytics pipeline  
- Statistical hypothesis testing  
- Regression modeling  
- Feature engineering techniques  
- Data visualization skills  

---

## 🔮 Future Improvements
- Apply advanced ML models (Random Forest, XGBoost)  
- Build real-time dashboard (Streamlit/Flask)  
- Include weather and pitch data  
- Add player form analysis  
- Integrate live APIs  

---

## 📌 Key Insights
- Batting first gives a measurable advantage  
- Scores have increased significantly over seasons  
- Powerplay and death overs are crucial phases  
- Strong predictive capability using regression models  

---

## 🔗 GitHub Repository
👉 https://github.com/AdityaAvhad/ipl-analytics

---

## 👤 Author
**Aditya Avhad**  
Roll No: SA201  
Class: SA2  
Subject: Data Analytics  
College: GH Raisoni International Skill Tech University
