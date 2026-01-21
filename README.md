# Hospital Emergency Room Dashboard (Power BI)

**Project Type:** Power BI Dashboard  
**Focus:** Emergency Room operational insights (Monthly View)  
**Tools:** Power BI Desktop, DAX, Data Modeling

---

## **Overview**
This project is a **Hospital Emergency Room Dashboard** built in **Power BI** to monitor ER performance and patient trends in a clear monthly view. The dashboard highlights key KPIs and breakdowns to support quick operational decision-making.

---

## **Key Metrics (KPIs)**
- **No. of Patients**
- **Average Wait Time (min)**
- **Patient Satisfaction Score**
- **No. of Patients Referred**

---

## **Dashboard Features**
- **Monthly filtering** (Year / Month slicers)
- KPI cards with formatted values (e.g., **36.67 min**)
- Demographic breakdowns (e.g., **Gender**, **Race**, **Age Group**)
- Visual trend indicators (sparklines / trend charts)
- *(Optional)* Conditional formatting / gradient coloring for better insights

---

## **DAX Highlights**
Examples of DAX used in this dashboard include:
- **Average Wait Time**
- **Waittime Status** (Within Target vs Target Missed)
- **Referral Count** (excluding blanks / “None”)
- **Time interval bucketing** using `SWITCH(TRUE())`

---

## **How to Use**
1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. Use the slicers (Year/Month) to filter the monthly view.
4. Explore visuals for trends and breakdowns.

---

## **Files in This Repository**
- **healthcare_dashboard.pbix** — Power BI report file  
- **Hospital ER_Data** — dataset  
- **README.md** — project documentation

---

## **Notes**
- This project is for learning/portfolio purposes.
- Ensure no sensitive or personally identifiable patient data is included before sharing publicly.

---

## **Author**
**Shachi Hardi**  
