
# 🏥 Healthcare Analytics Project

## 📌 Overview
This project demonstrates **healthcare data analytics and visualization** using **synthetic (dummy) data**.  
It simulates patient admissions, readmissions, departmental costs, and outcomes — providing a realistic but safe way to showcase data engineering + analytics skills.

All data here is **synthetic** and generated with Python (no real PHI/PII).  

---

## 📊 Dataset
- **File**: `healthcare_readmission_data.csv`
- **Records**: 500 patients (synthetic)
- **Fields**:
  - `PatientID` – Unique identifier
  - `AgeGroup` – Patient age group
  - `Gender` – Male/Female
  - `Department` – Hospital department (ICU, Cardiology, Oncology, etc.)
  - `AdmissionDate` – Date of admission
  - `DischargeDate` – Date of discharge
  - `LengthOfStay` – Days in hospital
  - `Readmitted` – 1 if patient was readmitted, else 0
  - `Cost` – Total hospitalization cost (synthetic values)

---

## 📈 Visualizations
The Jupyter Notebook `healthcare_visualizations.ipynb` includes:

1. **Monthly Readmission Rate**
   - Line chart of readmission rates over time.

2. **Total Healthcare Costs by Department**
   - Bar chart comparing costs across different departments.

3. **Readmission Rate by Department**
   - Bar chart showing which departments have higher/lower readmission ratios.

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/healthcare-analytics.git
   cd healthcare-analytics
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook healthcare_visualizations.ipynb
   ```

---

## 🛠 Skills Demonstrated
- **Data Engineering**: ETL-style preprocessing with Pandas
- **Healthcare Analytics**: Readmission KPIs, cost metrics
- **Visualization**: Matplotlib for trends & insights
- **Portfolio**: End-to-end project ready for GitHub

---

## ⚠️ Disclaimer
This project uses **synthetic, randomly generated data**.  
It does **NOT** contain any real patient information and is safe to share publicly.

---
