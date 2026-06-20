# Hospital Management System Analytics 🏥

## 📌 Project Overview
Welcome to my first data analytics portfolio project! This project demonstrates how database management and data visualization can optimize healthcare operations. Using **MySQL** for data extraction and **Tableau** for visual storytelling, I analyzed a hospital management database containing tracking records for patients, doctor specialties, room capacities, and prescriptions to uncover critical operational insights.

📊 **[View Interactive Tableau Dashboard Here](https://public.tableau.com/views/HospitalManagement_17750413382830/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 🛠️ Tech Stack & Skills Used
- **Database Engine:** MySQL (Advanced Joins, CTEs, Window Functions, CASE Statements, Aggregate Queries)[cite: 1]
- **Data Visualization:** Tableau Public[cite: 2]
- **Domain:** Healthcare Operations & Resource Management

---

## 🔍 Core Queries & Business Questions Solved
Using MySQL Workbench, I wrote targeted queries to solve key administrative and operational questions[cite: 1]:
1. **Patient Demographics:** Segmented emergency appointments into age groups (Pediatric, Adult, Geriatric) using conditional logic[cite: 1].
2. **Resource Optimization:** Identified room capacities across various sectors, specifically isolating bed allocations within high-priority departments like Neurology[cite: 1].
3. **Staffing Allocation:** Analyzed doctor distribution across hospitals to identify medical coverage levels[cite: 1].
4. **Prescription Tracking:** Uncovered the most frequently prescribed medications to support hospital pharmacy inventory tracking[cite: 1].

---

## 💡 Key Insights & Deliverables
- **Workload Analysis:** Mapped doctor counts by specialty, highlighting key concentrations in fields like Pediatrics and Cardiology to understand resource distribution[cite: 1, 2].
- **Capacity Mapping:** Utilized ranking window functions (`DENSE_RANK`) to successfully identify the department with the second-largest room capacity in each hospital, ensuring proper resource awareness[cite: 1].
- **Medication Utilization:** Discovered that **Propranolol** represents the highest prescription volume at **27.78%**, followed closely by **Paracetamol at 22.22%**, offering critical insights for pharmacy supply chains.
