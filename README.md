## 📖 Project Overview

This project is a case study in healthcare analytics using **Power BI**. It focuses on analyzing two datasets — *Patient Medical Records* and *Hospital Treatment Details* — to uncover trends, improve patient outcomes, and optimize hospital operations.

The project demonstrates complete workflow steps: **data cleaning, modeling (using DAX), dashboard creation, and storytelling with insights.**

✅ *Verified by **AlmaBetter Edutech Pvt. Ltd.***

---

## 🎯 Objective

The goal of this project is to design a comprehensive **Power BI dashboard** that provides:

* Insights into patient demographics and treatment outcomes.
* Cost analysis of medical procedures and hospital expenses.
* Hospital performance comparisons (patient load, cost efficiency, recovery ratings).
* Time-based trends in admissions, discharges, and length of stay.
* Visualization of treatment effectiveness linked with recovery ratings.

---

## 📂 Data Sources

1. **HealthcareDataset1.xlsx** – Patient Medical Records

   * PatientID, PatientName, Age, Gender, BloodType
   * Diagnosis, Treatment, AdmissionDate, DischargeDate, TotalBill
   * Full Prescription Details

2. **HealthcareDataset2.xlsx** – Hospital Treatment Details

   * PatientID, Hospital, DoctorName, RoomNumber
   * DailyCost, TreatmentType, RecoveryRating

---

## ⚙️ Process

1. **Data Cleaning** – Handled missing values, standardized dates, calculated *Length of Stay*, normalized cost columns.
2. **Data Modeling** – Built a star schema with fact and dimension tables. Established relationships using PatientID and Date.
3. **DAX Measures** – Created KPIs such as Total Patients, Average Length of Stay, Average Recovery Rating, Total Revenue, etc.
4. **Dashboard Design** – Designed an interactive and visually engaging Power BI dashboard with slicers and filters.
5. **Insights & Storytelling** – Highlighted key trends and provided recommendations for better patient care and hospital efficiency.

---

## 📊 Dashboard Features

* **Overview**: KPIs on patient count, costs, length of stay, recovery ratings.
* **Demographics**: Age, gender, blood type distribution.
* **Diagnosis & Treatments**: Frequency and distribution of diseases and treatments.
* **Cost Analysis**: Daily and total costs by hospital and treatment.
* **Hospital Performance**: Compare hospitals on costs, recovery ratings, and patient volume.
* **Treatment Effectiveness**: Relationship between length of stay and recovery.
* **Time Trends**: Admissions, discharges, and costs over time.

---

## 🔍 Key Insights

* Patient demographics significantly influence recovery and hospital stay length.
* Certain treatments show higher costs but lower recovery ratings, requiring optimization.
* Some hospitals demonstrate better efficiency and outcomes at lower costs.
* Seasonal spikes in admissions affect hospital workload and costs.

---

## ✅ How to Use

1. Download the datasets (`HealthcareDataset1.xlsx` and `HealthcareDataset2.xlsx`) and place them in the `data/` folder.
2. Open the `Healthcare_Dashboard.pbix` file in **Power BI Desktop**.
3. Refresh the data to load the latest datasets.
4. Use filters (hospital, treatment type, diagnosis) to explore insights interactively.

---

## 🛠️ Tech Stack

* **Languages & Tools**: Python (for ETL), SQL, Power BI, Excel
* **Platforms**: Power BI Desktop
* **Frameworks**: DAX (for advanced analytics)

---

## 📌 Future Scope

* Add predictive models for patient length of stay and readmission risk.
* Deploy dashboard on Power BI Service for real-time collaboration.
* Perform advanced text analytics on prescription details.

---

## 📜 License

This project is for **educational and portfolio purposes**. You may fork and adapt it with proper attribution.

---

✨ This project showcases how **data-driven insights can advance healthcare decision-making** by improving patient care and optimizing hospital efficiency.

✅ *Verified by **AlmaBetter Edutech Pvt. Ltd.***

