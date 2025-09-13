# 📊 Indian Patent Data Analysis Dashboard (2019)

A simulated real-world business intelligence project analyzing Indian patent filings and grants for the year 2019. This project replicates an internal analytics assignment using public data, with the goal of showcasing data cleaning, modeling, and dashboarding skills in Power BI.

---

## 📘 Overview

The aim of this project is to provide key insights into Indian patent trends using raw data extracted from Kaggle. The dataset contained inconsistencies, duplicate values, and formatting issues, requiring thorough data cleaning and transformation before analysis.

This project simulates a real client scenario for an IP consulting firm interested in:
- Patent grant trends
- Top applicants
- Field-wise distribution
- Grant processing timelines

---

## 📂 Dataset

- **Source:** [Kaggle – Indian Patent Data 2019](https://www.kaggle.com/)
- **Format:** Excel (.xlsx)
- **Rows:** 55,000+ entries
- **Columns include:**
  - Application Number
  - Applicant Name
  - Application Date
  - Publication Date
  - Field of Invention
  - Status (Granted, Filed, etc.)
  - IPC Classification
  - Inventor Info

---

## 🧼 Data Cleaning & Preparation

Data cleaning was performed using **Excel** and **Power Query** in Power BI:

- Removed duplicates based on `Application Number`
- Cleaned and standardized `Applicant Name` to group similar entities (e.g., "Samsung Inc" and "Samsung Co Ltd")
- Removed unnecessary spaces, null values, and special characters
- Converted dates into proper datetime formats
- Created calculated columns and measures using **DAX**

---

## 🧮 KPIs & Measures

The following KPIs were calculated using DAX:

- ✅ **Total Patents Filed**
- ✅ **Granted Patents**
- ✅ **Grant Percentage**
- ✅ **Average Grant Time** (in days)
- ✅ **Pharmaceutical Patent Ratio**
- ✅ **Patents Filed Per Month** *(optional line chart)*

---

## 📊 Dashboard Highlights

The interactive **Power BI Dashboard** includes:

- 📌 **KPI Cards** for total filings, grants, and percentages
- 📌 **Top 5 Applicants** by patent count
- 📌 **Field of Invention Breakdown** (bar chart / tree map)
- 📌 **Grant Timeline Trend** (line chart or area chart)

🎨 Includes custom design elements:
- Indian flag in the header
- Clean background layout
- Custom color palette

---

## 💡 Key Insights

- Over **XX,XXX** patents were filed in 2019, with a grant rate of approximately **XX%**
- **Top filers** included companies in electronics, pharmaceuticals, and IT
- **Pharmaceuticals** accounted for ~X% of all patent filings
- Average time from application to grant was **X days**

---

## 🛠 Tools Used

| Tool         | Purpose                              |
|--------------|---------------------------------------|
| Excel        | Initial data cleaning                 |
| Power Query  | Data transformation in Power BI       |
| Power BI     | Data modeling, DAX, visualization     |
| DAX          | KPI & calculated field development    |
| GitHub       | Version control and project showcase  |

---

## 🧑‍💼 Simulated Client Scenario

**Client:** An IP consulting firm helping tech and pharma companies manage their patent portfolios.

**Ask:** Create a dashboard to track:
- Filing trends
- Grant timelines
- Leading applicants
- Technology areas with most activity

**My Role:** Junior Data Analyst responsible for data cleaning, dashboard design, and KPI development.

---

## 🚀 Future Enhancements

- Add **multi-year trend analysis** using data from 2020-2023
- Include **geospatial mapping** of applicant locations
- Automate data refresh using Power BI service or APIs
- Add a **comparative view** by applicant nationality

---

## 📁 How to Use

1. Download or clone the repository.
2. Open the Power BI file (`Indian_Patent_Analysis_2019.pbix`) in Power BI Desktop.
3. Explore interactive visuals using slicers and filters.
4. Modify or update the Excel source if needed.
5. Click “Refresh” in Power BI to sync data.

---

## 👤 Author

**Pushpinder Sharma**  
*Junior Data Analyst*  
📅 2025  
