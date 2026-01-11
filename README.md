# 🚕 Ride-Hailing Conversion Funnel Analysis (Namma Yatri Datathon)

This project analyzes the end-to-end **conversion funnel, cancellations, and behavioral patterns**
in a ride-hailing platform using real datathon data provided by **Namma Yatri**.

The objective is to identify **drop-off points**, **cancellation drivers**, and propose
**data-backed product improvements**.

---

## 🎯 Problem Statements Covered

### Q1. Conversion Funnel Deep Dive
- Funnel stages: **Search → Quote → Booking → Completed**
- Segmentation by:
  - Time of day (Morning, Day, Evening, Night)
  - Trip length (Short, Medium, Long)
- Identification of **maximum drop-off stages**
- Hypothesis-driven analysis for observed drops

### Q2. Booking Cancellations
- Overall cancellation rate
- Driver vs Rider cancellations
- Analysis by pickup distance & trip distance
- Top driver cancellation reasons
- Relationship between **driver rating and cancellations**

### Q3. Critical Stage & Root Cause Analysis
- Identification of most critical funnel stage
- Behavioral segmentation of drivers/riders
- Weekly time-series trends for conversion and cancellations
- Product intervention recommendations

### Q4. Funnel Visualization & Storytelling
- Funnel visualizations (overall & segmented)
- Severity-based interpretation
- Executive-level storytelling using dashboards

---

## 🛠 Tools & Technologies

- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **SQL concepts**: Joins, funnel logic, aggregation
- **Power BI**: Funnel charts, KPIs, slicers, DAX
- **Jupyter Notebook**: Data cleaning & analysis

---

---

## 📁 Dataset Note

The raw datasets are **not included** in this repository due to GitHub file size limits (>100MB).

The analysis was performed on real datathon data:
- `search_data.csv`
- `quote_data.csv`
- `booking_data.csv`
- `booking_cancellation_data.csv`

The notebook will run correctly when these files are placed in the project root.

---

## 🔍 Key Insights (Summary)

- Highest funnel drop observed at **Quote → Booking**, especially for **long trips at night**
- Driver cancellations increase significantly for **low-rated drivers**
- Peak-hour demand shows higher search volume but lower conversion
- Product interventions like **dynamic pricing visibility** and **driver incentives**
  can improve conversions

---

## 👩‍💻 Author

**Srija Das**  
Email: dassrija217@gmail.com

LinkedIn: https://www.linkedin.com/in/srija-das-316496299/

## 📊 Power BI Dashboard Preview:
<img width="1414" height="791" alt="dashboard" src="https://github.com/user-attachments/assets/eabd8b94-f239-47c0-bf46-10a192ae6b82" />
