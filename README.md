# 📊 Field Activity Validity KPI Engine
### SQL‑Driven Validation Logic + Power BI Dashboards

This project was developed to address a decline in conversion rates driven by doctor recommendations across 10+ MEA Markets. To understand the root causes, we analyzed field activity behaviors logged by sales representatives — especially around call submissions, product detailing, and on‑ground engagement.

The goal: **establish data‑driven KPIs to measure the authenticity, quality, and compliance of field interactions.**

---

## 🚀 Key KPIs Implemented

### ✅ **1. Call & Detailing Location Match**
Ensures that the sales representative was physically present at the doctor’s location when detailing products (e.g., Sensodyne).

### ✅ **2. Time Gap Between Consecutive Calls**
Calculates the minutes between each rep’s calls to detect:
- Unusually fast submissions  
- Pattern-based anomalies  
- Productivity insights  

### ✅ **3. Call vs. Detailing Timestamp Validation**
Checks whether calls are genuinely captured during the detailing window and not batch‑submitted later.

### ✅ **4. Business‑Hours Compliant Calls**
Flags activities submitted:
- Before or after working hours  
- On weekends / non‑working days  
- Outside country-specific time windows  

Each country follows its own weekly holiday + timing logic.

---

## 📈 Power BI Dashboards Developed

Dashboards were designed across multiple hierarchical levels:

- **Country-level performance visibility**  
- **Manager-level compliance insights**  
- **Representative-level activity monitoring**  

These dashboards help commercial leadership:

🔹 Monitor field force effectiveness  
🔹 Detect compliance risks early  
🔹 Improve doctor engagement quality  
🔹 Reduce inefficiencies and suspicious behavior  
🔹 Strengthen data integrity and trust  

---

## 🧠 Full SQL Logic  
The Attached SQL script performs:

✔ Geolocation validation using Haversine  
✔ Timestamp normalization using country-specific time zones  
✔ Call validity classification  
✔ Time-difference metrics (consecutive calls, call vs. detailing)  
✔ Final validation logic combining all rules  

🛠 Tech Stack

## 🛠 Tech Stack

| Technology / Tool | Purpose |
|-------------------|---------|
| **SQL (Databricks / Spark SQL)** | Core business logic, KPI computation, geospatial validation (Haversine) |
| **Power BI** | Interactive dashboards, multi-level reporting (country, manager, rep) |
| **Salesforce Veeva CRM** | Primary source for call, detailing, and activity logs |
| **Geospatial Calculations** | Validates location match between Check-In & CLM coordinates |
| **Timezone Conversions** | Normalizes timestamps using country-specific business hours |
| **Data Modeling** | Transforming raw activity logs into structured KPI datasets |
| **Python (Optional)** | Supporting scripts for data prep (if needed) |
| **Version Control (GitHub)** | Tracking SQL logic and project documentation |

🏁 Outcomes & Impact
This solution transformed raw field logs into actionable performance intelligence, enabling leadership teams to make stronger, data-backed decisions.
Key business outcomes achieved:
✨ Improved field force productivity
✨ Higher quality doctor interactions
✨ Lowered irregular submissions
✨ Stronger compliance governance
✨ More trust in Salesforce activity data

👤 Author
Noor Jan
MEA Expert Data Analyst

```sql
PASTE YOUR FULL SQL SCRIPT HERE (too large to include in this readme response box)
