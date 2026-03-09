# 🫀 Heart Disease Analysis Using Tableau Visualization

> **Heartbeat of Data — A Visual Journey Through Heart Disease Risk Factors**

![Tableau](https://img.shields.io/badge/Tableau-Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Python](https://img.shields.io/badge/Python-Flask-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📋 Project Details

| Field | Details |
|-------|---------|
| **Project Name** | Heart Disease Analysis Using Tableau Visualization |
| **Tools Used** | Tableau Public, MySQL, Python, Flask |
| **Dataset** | Heart_new2.csv — 4,500 rows, 18 columns |


---

## 📌 Problem Statement

Cardiologists, health policymakers, and individuals lack a centralized, visual, and interactive tool to analyze heart disease risk factors from multi-variable patient data. Raw patient records across 18 variables — including BMI, smoking, age, gender, diabetes, and physical activity — are difficult to interpret without proper visualization, leading to delayed or uninformed clinical and policy decisions.

---

## 🎯 Objective

- Analyze heart disease risk factors across 4,500 patient records
- Build 10 interactive Tableau visualizations
- Create 1 comprehensive Dashboard and 1 Tableau Story
- Embed the dashboard in a Flask web application
- Publish the complete solution on Tableau Public

---

## 📊 Dataset Information

| Property | Value |
|----------|-------|
| **File Name** | Heart_new2.csv |
| **Total Records** | 4,500 rows |
| **Total Features** | 18 columns |
| **Heart Disease — Yes** | 483 cases (10.7%) |
| **Heart Disease — No** | 4,017 cases (89.3%) |
| **Gender Split** | Female: 2,604 / Male: 1,896 |

### Key Columns
- **Target Variable:** HeartDisease (Yes / No)
- **Lifestyle:** Smoking, AlcoholDrinking, PhysicalActivity, SleepTime
- **Clinical:** BMI, Stroke, Diabetic, GenHealth
- **Demographics:** AgeCategory, Sex, Race
- **Co-morbidities:** Asthma, KidneyDisease, SkinCancer, DiffWalking

---

## 📈 Visualizations Created

| # | Title | Chart Type | Key Finding |
|---|-------|-----------|-------------|
| 1 | Gender wise Heart Disease | Stacked Bar | Males at higher risk (13.5%) vs Females (8.7%) |
| 2 | Age wise Heart Disease | Grouped Bar | Peak risk at age 65–69 |
| 3 | Diabetics vs Stroke | Scatter Plot | Diabetics show higher stroke counts |
| 4 | Smoking & Alcohol Impact | Horizontal Bar | Smokers show 139 HD cases |
| 5 | Stroke vs Other Diseases | Bar Chart | Stroke co-occurs with Asthma, Kidney, Skin Cancer |
| 6 | Race wise Heart Disease | Pie Chart | White: 75.57%, Black: 17.81% |
| 7 | General Health vs HD | Bubble Chart | Good health still shows 172 HD cases |
| 8 | Physical Activity vs HD | Donut Chart | Active: 3,231 vs Inactive: 1,269 |
| 9 | Age & BMI vs Diabetic | Treemap | Higher BMI in older diabetic groups |
| 10 | Triple Threat Analysis | Grouped Bar | Age + Diabetic + HD cross analysis |

---

## 🔗 Live Links

| Resource | Link |
|----------|------|
| 📊 **Tableau Dashboard** | [View Dashboard](https://public.tableau.com/views/dashboard_17726415994650/Dashboard1) |
| 📖 **Tableau Story** | [View Story](https://public.tableau.com/views/Book_17726265026180/Story1) |
| 🎬 **Demo Video** | [Watch Demo](https://drive.google.com/file/d/1iuU5TWMTX7vtTUzDAlU3DPVvA03iTKab/view?usp=sharing) |

---

## 🛠️ Technology Stack

| Layer | Technology |
|-------|-----------|
| Data Source | Heart_new2.csv |
| Database | MySQL |
| Visualization | Tableau Public |
| Web Framework | Python Flask |
| Frontend | HTML, CSS, JavaScript |
| Hosting | Tableau Public Cloud |

---

## 🗂️ Project Structure
```
Heart-Disease-Analysis/
│
├── app.py                  # Flask application
├── Heart_new2.csv          # Dataset
│
├── templates/
│   └── index.html          # Main HTML page with Tableau embeds
│
├── static/
│   └── assets/
│       ├── css/
│       ├── js/
│       └── img/
│
└── README.md
```

---

## ⚙️ How to Run Locally

**Step 1:** Clone the repository
```bash
git clone https://github.com/Shripatil9082/Heart-Disease-Analysis.git
```

**Step 2:** Navigate to the project folder
```bash
cd Heart-Disease-Analysis
```

**Step 3:** Install Flask
```bash
pip install flask
```

**Step 4:** Run the application
```bash
python app.py
```

**Step 5:** Open browser and go to
```
http://127.0.0.1:5000
```

---

## 💡 Key Insights

1. **Males aged 55–74** show the highest heart disease rates in the dataset
2. **Diabetic patients** have significantly elevated stroke risk
3. Even patients with **Good self-rated health** developed heart disease
4. **Physical activity** strongly correlates with lower heart disease risk — 71.8% of patients are active
5. **Smoking**, even without alcohol, is a strong independent risk factor

---

## 📅 Project Planning

| Sprint | Stories | Points | Duration | Status |
|--------|---------|--------|----------|--------|
| Sprint 1 | USN-1 to USN-4 | 14 pts | 4–10 March 2026 | ✅ Completed |
| Sprint 2 | USN-5 to USN-10 | 12 pts | 11–17 March 2026 | ✅ Completed |
| **Total** | **10 Stories** | **26 pts** | **14 Days** | ✅ |

---



---

## 🏫 Institution

**D Y Patil Agriculture & Technical University, Talsande**
MCA Sandwich Program


---

## 📄 License

This project is submitted as part of an academic  program.
Dataset sourced from Kaggle — for educational purposes only.

---

> ⭐ If you found this project helpful, please give it a star!
