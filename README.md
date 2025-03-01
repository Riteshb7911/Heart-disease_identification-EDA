# ❤️ Heart Disease Prediction – Exploratory Data Analysis (EDA) 🏥
## 📌 Problem Statement
Heart disease remains one of the leading causes of death worldwide. Understanding key risk factors through Exploratory Data Analysis (EDA) can provide valuable insights into early detection and prevention. This project focuses on analyzing patient health data to identify patterns and trends related to heart disease.

## 📊 Dataset Description  

The dataset consists of **14 features** that provide critical health indicators for heart disease analysis:  

| 🔢 **Feature Name**   | 📌 **Description** |
|----------------------|--------------------------------------------------|
| 🎂 **age**           | Age of the patient  |
| 🚻 **sex**           | Gender of the patient (`0: Female`, `1: Male`)  |
| ❤️ **cp**           | Chest pain type (`0: Typical Angina`, `1: Atypical Angina`, `2: Non-Anginal Pain`, `3: Asymptomatic`) |
| 💓 **trestbps**      | Resting blood pressure (mm Hg) |
| 🩸 **chol**         | Serum cholesterol level (mg/dL) |
| 🍬 **fbs**          | Fasting blood sugar (`0: <120 mg/dL`, `1: >120 mg/dL`) |
| 📈 **restecg**      | Resting electrocardiographic results (`0: Normal`, `1: ST-T wave abnormality`, `2: Left ventricular hypertrophy`) |
| 🏃 **thalach**      | Maximum heart rate achieved |
| 🚶 **exang**        | Exercise-induced angina (`0: No`, `1: Yes`) |
| 🔽 **oldpeak**      | ST depression induced by exercise relative to rest |
| 📉 **slope**        | Slope of the peak exercise ST segment (`0: Upsloping`, `1: Flat`, `2: Downsloping`) |
| 🔢 **ca**           | Number of major vessels colored by fluoroscopy (`0-4`) |
| 🧬 **thal**         | Thalassemia type (`0: Normal`, `1: Fixed Defect`, `2: Reversible Defect`) |
| ⚠️ **target**       | Presence of heart disease (`0: No Disease`, `1: Disease`) |

## 🎯 Objective
The goal of this project is to perform Exploratory Data Analysis (EDA) to uncover insights about heart disease risk factors and patterns in patient data. This helps:

✅ Understand key health indicators associated with heart disease.

✅ Identify trends and correlations within the dataset.

✅ Assist healthcare professionals in data-driven decision-making.

## ⚙️ Methodology
1️⃣ Data Preprocessing

✅ Checked for missing values and handled inconsistencies.

✅ Encoded categorical variables for analysis.

✅ Normalized & scaled numerical features for better visualization.

2️⃣ Exploratory Data Analysis (EDA)
* 📊 Feature distribution visualizations to understand trends in patient data.
* 🔍 Correlation analysis to determine relationships between risk factors.
* 📈 Boxplots & histograms to detect outliers in cholesterol, blood pressure, and heart rate.
* 📉 Heatmaps to visualize the correlation between variables affecting heart disease.
* 🩺 Comparative analysis of patients with and without heart disease.
## 📌 Key Takeaways
✅ Age, chest pain type, cholesterol levels, and resting blood pressure are strong indicators of heart disease.

✅ Patients with higher maximum heart rate (thalach) tend to have a lower risk of heart disease.

✅ Exercise-induced angina (exang) and ST depression (oldpeak) show significant correlations with heart disease presence.

✅ Outliers detected in cholesterol and blood pressure values, requiring further investigation.

## 🚀 Future Improvements
* Apply advanced statistical tests to validate findings.
* Feature engineering to create more informative variables.
* Expand dataset to include additional medical parameters (e.g., lifestyle habits, family history).
* Train machine learning models to predict heart disease based on EDA insights.
