# insurance-analytics-project
This mock analytics project showcases how an insurance company might use **Databricks** and **Power BI** to analyze claims, policyholders, and adjuster performance. Built by [Eric Meers-Berg](mailto:emeersberg@gmail.com), it simulates an end-to-end enterprise reporting pipeline — from raw data to actionable dashboards.

---

## 🔧 Tech Stack

- **Databricks (Community Edition)** – data wrangling and analysis using PySpark
- **Power BI** – interactive dashboards for executive insights
- **GitHub** – version control and project documentation
- **CSV Files** – synthetic data for policies, claims, and adjusters

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Policy_Holders_v3.csv` | Mock dataset of policyholders |
| `Claims_v3.csv` | Mock claims data including type, status, and amount |
| `Adjusters_v3.csv` | Adjuster assignment info |
| `insurance_project_notebook.ipynb` | Jupyter notebook with PySpark code for cleaning, joining, and analyzing data |
| `insurance_dashboard.pbix` | Power BI file with visuals (claims by type, payout analysis, adjuster performance, etc.) |

---

## 📊 Sample Power BI Visuals

> *(Screenshots coming soon)*

Planned visuals include:

- Total claims and payouts by policy type
- Adjuster productivity metrics
- Monthly claim trends
- High-risk policyholder identification

---

## 💡 Key Features

- Data cleaning and joins across three datasets
- Business logic applied to simulate real-world KPIs
- Power BI dashboards for storytelling and operational use
- Clear file structure and well-commented code for easy reuse

---

## 🚀 How to Run

1. **Databricks**:
   - Import the notebook to your workspace
   - Upload CSVs to `/FileStore/tables/`
   - Run each cell step by step

2. **Power BI**:
   - Open `.pbix` file
   - Refresh data source to re-point to CSVs (or web links)

---

## 🔍 Future Improvements

- Connect directly to Databricks SQL (Pro version)
- Add more granular metrics by claim type and adjuster
- Incorporate anomaly detection logic

---

## 📬 Contact

Eric Meers-Berg  
[emeersberg@gmail.com](mailto:ericmeersberg@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/your-link)

---

> This is a mock project for portfolio demonstration only — no real customer data is used.
