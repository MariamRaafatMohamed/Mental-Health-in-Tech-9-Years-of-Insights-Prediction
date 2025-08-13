# 🧠 Mental Health in Tech: 9 Years of Insights & Prediction

## Overview
This project analyzes and models **9 years of data (2014–2023)** from the **OSMI Mental Health in Tech Survey** to explore trends, patterns, and factors affecting mental health in the technology industry.

It combines **data cleaning, exploratory analysis, interactive dashboards, clustering analysis, and machine learning modeling** to both **understand the problem** and **predict the likelihood of seeking treatment**.

---

## Objectives
- Merge and clean survey data from **2014 to 2023**.
- Perform **in-depth exploratory data analysis (EDA)**.
- Apply **clustering analysis** to group respondents based on shared characteristics.
- Build **interactive Power BI dashboards** for stakeholder insights.
- Create **visualizations** for trend analysis across years.
- Develop a **machine learning model** to predict whether a respondent is likely to seek treatment.
- Present findings in a **professional presentation** for competition judging.

---


---

## Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, Plotly, Seaborn, Matplotlib)
- **Power BI** (Interactive dashboards & data modeling)
- **Jupyter Notebook** (Analysis, clustering & ML modeling)
- **Canva** (Presentation design)
- **Kaggle** (Collaboration & version control of notebooks)

---

## Data Preparation
- Collected yearly datasets (2014–2023) from **OSMI Mental Health in Tech Survey**.
- Standardized column names across years.
- Merged into a **single dataset**.
- Cleaned missing values, encoded categorical variables, and grouped age into bands.
- Final **clean dataset shape**: *~30,000+ rows × standardized features*.

---

## Exploratory Data Analysis
- **Demographic distribution** (gender, country, age groups).
- **Trends in treatment seeking** across years.
- **Impact of workplace factors** (benefits, anonymity, leave policies).
- **Correlation heatmap** of features.
- Visualized:
  - Bar charts
  - Pie charts
  - Line charts
  - Heatmaps
  - Geographic maps (country-level mental health trends)

---

## Clustering Analysis
**Goal:** Identify natural respondent groups based on mental health indicators and demographics.

- **Algorithm:** K-Means Clustering.
- **Feature selection:** workplace factors, demographics, and treatment history.
- **Scaling:** StandardScaler applied to numerical features.
- **Number of clusters:** Selected using the Elbow Method & Silhouette Score.
- **Visualization:**  
  - 2D scatter plots (colored by cluster).
  - **3D scatter plot** showing relationships between 3 main principal components.
- **Cluster profiling:** Calculated summary statistics for each cluster.

**Outputs generated:**
- `mental_health_cleaned.csv` (full cleaned dataset)
- `cluster_summary.csv` (aggregate stats per cluster)

---

## 📈 Power BI Dashboard
Uploaded **two datasets**:
1. **Mental Health Cleaned** – full cleaned survey data.
2. **Cluster Summary** – aggregated statistics for each cluster.

**Data modeling:** Created relationships between the two datasets inside Power BI.

**Dashboard Pages:**
1. **Overview & Demographics** – participant distribution by gender, age, and country.
2. **Mental Health** – yearly treatment trends, workplace factors impact.
3. **Summary** – key KPIs and overall metrics.
4. **Cluster** – interactive visuals showing respondents grouped by cluster ID.
5. **Cluster Summary Stats** – profile comparison between clusters.

---

## 🤖 Machine Learning Model
**Goal:** Predict if a person is likely to seek mental health treatment.
- Features: `gender`, `country`, `self_employed`, `family_history`, `work_interfere`, `no_employees`, `tech_company`, `benefits`, `care_options`, `wellness_program`, `seek_help`, `anonymity`, `leave`, `age_group`
- Preprocessing: **Ordinal Encoding** of categorical variables.
- Model tested:
  - Logistic Regression
  - Random Forest
  - XGBoost (best performer)
- Best model: **XGBoost** & **Logistic Regression** with accuracy **~82%** and AUC score **~0.82**.

---

## 📑 Presentation
Designed in **Canva**:
- Introduction
- Problem Statement
- Objective of Analysis
- Data Overview
- Cleaning & Preprocessing
- Key Insight
- Conclusion & Recommendations

---

## 🏆 Competition Achievement
This project won **4th place** in the final competition of the **Instant AI course**.

---

## 📎 Links
- 📓 Kaggle Notebook: [Kaggle Notebook](https://www.kaggle.com/code/mariamraafatbrownies/mental-health-tech-9-years-of-insights-prediction)
- 🎥 Presentation: [Presentation](https://www.canva.com/design/DAGv69muVfM/ULRK1f3baq_7mS493E8kbQ/edit?utm_content=DAGv69muVfM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- 📄 Dataset: [2014](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) 
- 📄 Dataset: [2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)
- 📄 Dataset: [2017](https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2017)
- 📄 Dataset: [2018](https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2018)
- 📄 Dataset: [2019](https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2019)
- 📄 Dataset: [2020](https://www.kaggle.com/datasets/osmihelp/osmi-2020-mental-health-in-tech-survey-results)
- 📄 Dataset: [2021](https://www.kaggle.com/datasets/osmihelp/osmh-2021-mental-health-in-tech-survey-results)
- 📄 Dataset: [2022](https://www.kaggle.com/datasets/osmihelp/osmh-mental-health-in-tech-survey-2022)
- 📄 Dataset: [2023](https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2023)


---

## Report Screenshots

![Overview & Demographics](Overview_&_Demographics.jpeg)

![Mental Health](Mental_Health.jpeg)

![Summary](Overview_&Summary.jpeg)

![Mental Health](Mental_Health.jpeg)

![Cluster](Cluster.jpeg)

![Cluster Summary Stats](Cluster_Summary_Stats.jpeg)

![modeling](modeling.jpeg)

