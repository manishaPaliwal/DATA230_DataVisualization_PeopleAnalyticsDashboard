# 📊 **People Analytics Dashboard**

## 📌 **Project Summary:**
This project is a data-driven exploration into **People Analytics**—using HR data to visualize, understand, and inform better workforce decisions. Inspired by the workplace shifts during the **“Great Resignation” era (2020-2021)**, our goal was to turn employee data into actionable insights via an interactive Tableau dashboard.

We analyzed patterns in **attrition, diversity, and tenure**, helping HR leaders uncover trends around employee exits, diversity representation, and retention risks.

---

## 🛠️ **How We Built It:**

✅ **Data Source:**
- Used an HR dataset of **22,438 employee records with 13 attributes** (name, gender, department, job title, race, hire/termination dates, etc.)  
- Cleaned the data by removing **224 NULL records** and filtering out inconsistent future termination dates.

✅ **Data Preparation:**
- Engineered new attributes including:
  - `Age` (from birthdate)
  - `Tenure` (years worked)
  - `Age of Exit`
  - `Employee Status` (Active/Inactive)
  - `Gender Diversity %`
  - `Race Diversity %`
- Created **groupings and bins**:
  - Age bins (20-30, 30-40, 40-50, 50+)
  - Gender grouping (Female + Non-conforming grouped as Female)
  - Race grouping (People of Color vs. White)

✅ **Dashboard Features:**
- Interactive parameters to toggle between **gender and race diversity views**.
- Employee-level drill-down with name selection.
- Hierarchical filters by **State → City**.
- Show/hide buttons to declutter dashboards.
- Dynamic sheets acting as filters across dashboards.

---

## 💡 **Unique Project Highlights:**

✨ Created a **custom Diversity parameter** to let users dynamically explore **gender vs. race diversity** across roles.  
✨ Built a **multi-layered dashboard combining fixed charts, action filters, and row-level security**.  
✨ Used Tableau’s **show/hide filter buttons** to keep visuals clean while enabling interactivity.  
✨ Integrated **advanced action filters linked to images stored in Tableau repository**.

---

## ✅ **Key Insights:**

1. **Balanced Gender Diversity**: Company shows >45% female representation across most departments.
2. **Race Diversity Gaps**: Some leadership roles (VP Sales, Attorney) show underrepresentation of People of Color.
3. **2021 Attrition Spike**: Highest termination rates coinciding with “Great Resignation”.
4. **Young Exit Risk**: Employees aged **24-26 are most likely to leave within 4 years**—possibly due to early-career shifts or value misalignment.

---

## 🎯 **What Went Well:**

🌟 Smooth integration of **custom calculated fields and hierarchical filters**.  
🌟 Dashboard design balanced **interactivity + readability** without overwhelming the user.  
🌟 Learned and applied **advanced Tableau features** (row-level security, dynamic filters, fixed calculation charts).  
🌟 Insights aligned well with known trends in post-pandemic workplace dynamics.

---

## ⚠️ **Challenges & Lessons Learned:**

😅 **Data limitations**: Used a publicly available “real-world fake” dataset; some variables like salary, performance ratings weren’t available for deeper insights.  
😅 Had to handle **future termination dates anomalies** without knowing underlying cause.  
😅 Representing **termination trends by percentage vs. raw counts** was a design debate to better reflect departmental impacts.

---

## 🚀 **Future Directions:**

➡️ Apply dashboard to **real company datasets** for validated business use cases.  
➡️ Integrate **additional employee attributes** (salary, skills, performance ratings) to connect attrition with other factors.  
➡️ Explore **AI-driven predictive models** to forecast resignations based on multivariate analysis.  
➡️ Develop tools to surface **bias detection** in hiring, promotion, and attrition using People Analytics.

