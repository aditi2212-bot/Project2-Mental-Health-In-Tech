# 🧠 Mental Health in Tech – Analysis Project

## 📌 Overview  
This project explores **mental health in the technology industry** using the OSMI survey dataset.  
The aim is to analyze workplace factors, demographics, and treatment-seeking behavior to understand how tech professionals deal with mental health challenges.  

The project includes:  
✅ Data Cleaning & Preprocessing  
✅ Exploratory Data Analysis (EDA)  
✅ Hypothesis Testing (Chi-Square & T-Test)  
✅ Interactive Visualizations (Plotly)  
✅ Key Insights  

---

## 📊 Dataset  
- Source: OSMI Mental Health in Tech Survey  
- Format: CSV  
- Size: ~1,200+ responses  
- Features include:  
  - `Age`, `Gender`, `Country`  
  - `work_interfere`, `remote_work`, `no_employees`  
  - `treatment`, `benefits`, `seek_help`  
  - and more  

---

## 🔍 Methodology  
1. **Data Cleaning**  
   - Handled missing values  
   - Standardized categorical columns (e.g., gender variations)  
2. **Exploratory Analysis**  
   - Demographics, company support, treatment vs workplace factors  
3. **Hypothesis Testing**  
   - *H1:* Benefits are associated with treatment (Chi-Square Test)  
   - *H2:* Age influences treatment-seeking behavior (T-Test)  
4. **Interactive Visualizations**  
   - Built with **Plotly** for interactive plots  

---

## 📈 Key Visualizations (Plotly)  
- Age vs Gender distribution  
- Company size vs Benefits  
- Gender & Treatment breakdown  
- Top 10 Countries of respondents  
- Work interference vs treatment  
- Correlation Heatmap  
- Remote work & treatment distribution  

---

## 📌 Insights  
- 🌍 Majority of respondents are from **US, UK, and Canada**  
- 👩‍💻 **Gender imbalance** exists in tech, but treatment rates are comparable  
- 🏢 Larger companies → more benefits → higher treatment rates  
- 💻 Remote work → lower stigma and higher comfort in seeking help  
- ⚖️ Hypothesis Testing:  
  - Benefits significantly affect likelihood of treatment  
  - Age is **not a strong factor** in treatment-seeking  

---

## 🚀 How to Run  

### 🔹 1. Clone the Repository  
```bash
git clone https://github.com/<your-username>/mental-health-in-tech.git
cd mental-health-in-tech
