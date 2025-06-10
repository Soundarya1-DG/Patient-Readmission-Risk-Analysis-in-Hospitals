# Patient-Readmission-Risk-Analysis-in-Hospitals
Hospital readmissions are a major concern for healthcare providers. This project focuses on analyzing patient data to identify patterns and predict which patients are at high risk of being readmitted within 30 days of discharge. This helps improve care quality and reduce costs.

## 📌 Project Overview
This project aims to identify patterns, trends, and factors that contribute to patient readmissions in hospitals. It uses machine learning models and statistical techniques to predict patient readmission risks and provides operational and executive-level dashboards using Excel, Power BI, and Tableau.

## problem statement
The goal was to predict the likelihood of a patient being readmitted to a hospital within 30 days of discharge. This helps hospitals reduce readmission rates, optimize resource allocation, and improve patient care quality

## 🎯 Objective
To analyze hospital data and predict which patients are at high risk of being readmitted, enabling healthcare providers to proactively improve patient care and reduce readmission rates.

## 🛠 Tools & Technologies Used
- **Excel**: Data cleaning, preprocessing, initial pivot analysis
- **Python (Pandas, Scikit-learn, Matplotlib, Seaborn)**: EDA, statistical testing, ML modeling
- **Statistics**: Correlation analysis, hypothesis testing
- **Power BI**: Operational dashboard for hospital staff
- **Tableau**: Storytelling dashboard for executive insights
- **GitHub**: Version control and documentation

## 📁 Project Structure
```
Patient_Readmission_Risk_Analysis/
├── README.md
├── data/
│   ├── original_dataset.csv
│   ├── cleaned_data.xlsx
│   └── model_output.csv
├── notebooks/
│   └── Readmission_Modeling.ipynb
├── powerbi/
│   └── Readmission_Dashboard.pbix
├── tableau/
│   └── Executive_Insights.twbx
├── reports/
│   ├── Final_Report.pdf
│   └── Project_Presentation.pptx
├── scripts/
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   └── train_model.py
└── visuals/
    ├── dashboard_screenshot.png
    └── eda_charts.png
```

## 📊 Key Findings
- 22% of patients were readmitted within 30 days
- Higher readmission rates were found in patients with chronic conditions and longer initial stays
- Departments like Cardiology and Oncology had the highest readmission ratios
- Readmitted patients had an average stay of 2.5 days longer than others

## 🤖 Machine Learning Summary
- **Model Used**: Random Forest Classifier
- **Accuracy**: 86%
- **Precision (Positive Class)**: 81%
- **Top Predictors**: Length of stay, prior admissions, diagnosis, department

## 📈 Dashboards
- **Power BI**:
  - KPIs: Avg Stay, Readmission %, Admissions
  - Department-wise and monthly trends
  - Slicers for Age, Gender, Diagnosis

- **Tableau**:
  - Heatmap: Readmissions by Department
  - Funnel Chart: Patient journey from Admission to Readmission
  - Storyline combining visuals and insights

## 📌 Business Impact
- Early prediction of readmission risk can reduce re-hospitalization and improve quality of care
- Operational dashboards enable department heads to target high-risk areas
- Executive reports guide strategic health planning and resource allocation

## 📎 How to Run
1. Clone this repo
2. Run `notebooks/Readmission_Modeling.ipynb`
3. Open Excel or dashboards in Power BI/Tableau folders to explore results

## 🙌 Author
Soundarya DG – Data Analyst | Python Developer | Healthcare AI Enthusiast

## 📬 Contact
Feel free to reach out via [LinkedIn](https://www.linkedin.com) or GitHub Issues if you have questions or suggestions.

---

> 📣 *This project was created as a comprehensive data analysis case study integrating end-to-end skills across the data science pipeline.*

