# University Academic Performance & Operations Analytics (Power BI)

## 📌 Project Overview
An end-to-end interactive Power BI reporting suite analyzing institutional performance across **6 faculties, 20 departments, 500 courses, and 10,000+ students**. Designed for university leadership to monitor enrollment trends, academic outcomes, student attendance, and lecturer workload balance.

---

## 🎯 Key Metrics & Findings
* **Institutional Scale:** 10K students enrolled across 6 faculties, 20 departments, and 500 courses.
* **Academic Outcomes:** Overall pass rate stands at **77.24%** with a university-wide average GPA of **2.32**, while the average graduation rate sits at **34.16%**—Highlighting a key retention and completion bottleneck.
* **Enrollment & Demographics:** Tracks student distribution across campuses, faculties, programmes, academic sessions, and gender.
* **Attendance & Engagement:** Monitors attendance rates across departments, courses, and lecturers to flag early absenteeism risks.
* **Faculty Workload:** Evaluates course assignments, credit unit distribution, and student-to-lecturer ratios by department.

---

## 📊 Dashboard Architecture

### 1. Executive Overview
High-level KPI scorecard tracking core institutional counts alongside critical performance indicators (Graduation Rate, Average GPA, and Pass Rate) with semantic alert color coding.
![Executive Dashboard Screenshot](<Executive Overview.png>).

### 2. Enrollment Overview
Breaks down student population by campus, faculty, programme, academic year, and gender distribution with interactive year filtering.
![Enrollment Overview Dashboard Screenshot](<Enrollemnet Overview.png>)

### 3. Academic Performance Dashboard
Evaluates GPA performance, Pass vs. Fail ratios, average scores across assessment types (Assignments, Midterms, Quizzes, Projects, Labs), and programme-level pass/failure rates.
![Academic Performance Dashboard Screenshot](<Academic Performance.png>)


### 4. Attendance Dashboard
Tracks average attendance percentages across academic sessions, departments, courses, and lecturers.
![Attendance Dashboard screenshot](<Attendance.png>)

### 5. Lecturer Dashboard
Analyzes teaching workload, distinct courses assigned, total credit units, and department-level student-to-lecturer ratios.
![Lecturer Dashboard screenshot](<Lecturer.png>)

---

## 🛠️ Tools & Techniques Used
* **Power BI Desktop:** Data modeling, DAX measures (`DISTINCTCOUNT`, `DIVIDE`, conditional formatting), and multi-page report design.
* **PostgreSQL / SQL:** Data extraction, relational joins, and pre-aggregation validation.
* **Design Standards:** 60-30-10 color hierarchy (Deep Navy `#1B365D`, Teal `#0D9488`, semantic Crimson `#EF4444` and Emerald `#10B981`) for insight-driven visual storytelling.

---

## 💡 Strategic Recommendations
1. **Retention & Graduation Intervention:** Investigate the gap between the **77.24%** course pass rate and **34.16%** graduation rate by auditing carry-over policies and academic advising in lower-GPA programmes.
2. **Workload Rebalancing:** Reallocate teaching assignments in departments with high student-to-lecturer ratios and standardize credit unit caps per lecturer.
3. **Early Attendance Monitoring:** Trigger automated advisor check-ins for courses and departments falling below the target attendance threshold.
