#   Hospital Emergency Room Dashboard

##   Overview

This project comprises a comprehensive **data visualization dashboard** designed to analyze and present key performance indicators (**KPIs**) and patient information for a **hospital emergency room (ER)**. The dashboard provides insights into **patient flow, wait times, satisfaction levels, referral patterns, and demographics**, enabling data-driven decision-making for improved operational efficiency and patient care.

The dashboard includes the following sections, each representing a distinct view of the ER data:

* **Monthly View**
* **Consolidated View**
* **Patient Details**
* **Key Takeaways**

##   Features

###   **I. Monthly View (July 2024)**

The **Monthly View** offers a snapshot of ER activity for July 2024. Data for this section is sourced from the "Monthly View" section of the provided document.

####   **Key Metrics:**

* **Total Patients:** 488
* **Average Wait Time:** 35.2 minutes
* **Patient Satisfaction Score:** 4.79
* **Patients Referred:** 198
* **Admission Rate:** 54.51% (266 Admitted / 222 Not Admitted)
* **Percentage of Patients Seen Within 30 Minutes:** 40.98%

####   **Visualizations:**

* Patient Admission Status distribution.
* Patient distribution by **age, gender, and race**.
* Referral patterns by **department**.
* Patient volume by **day and hour**.

###   **II. Consolidated View (October 2023 - October 2024)**

The **Consolidated View** provides an overview of ER performance across a year, from October 2023 to October 2024. Data for this section is sourced from the "Consolidated View" section of the provided document.

####   **Key Metrics:**

* **Total Patients:** 9070
* **Average Wait Time:** 35.3 minutes
* **Patient Satisfaction Score:** 4.99
* **Total Patients Referred:** 3750
* **Admission Rate:** 50.04% (4539 Admitted / 4531 Not Admitted)
* **Percentage of Patients Seen Within 30 Minutes:** 40.65%

####   **Visualizations:**

* Aggregate patient data over the year.
* Trends in **wait times, admissions, and referrals**.
* Comparison of **patient demographics** over the year.

###   **III. Patient Details**

This section provides **granular patient-level data** for in-depth analysis of individual patient encounters. Information for this section is based on the "Patient Details" section of the provided document.

####   **Key Data Points:**

* Patient ID
* Full Name (Anonymized)
* Gender
* Age
* Admission Date
* Race
* Wait Time
* Department Referred
* Admission Status

###   **IV. Key Takeaways**

A summary of the most significant findings and **actionable insights** derived from the dashboard (April 2023 - October 2024). Information for this section is from the "Key Takeaway" section of the provided document.

####   **Key Findings:**

* **Average Wait Time:** Approximately 35.3 minutes
* **Patient Satisfaction Score:** 4.99 out of 10
* **Referral Patterns:** A significant number of patients (5400) did not require referrals; among those referred, the most common were General Practice (1840 cases) and Orthopedics (995 cases).
* **Peak Busy Periods:** Busiest days were Mondays (1377 patients), Saturdays (1322 patients), and Tuesdays (1318 patients); busiest hours were 11 AM, 7 PM, 1 PM, and 11 PM.
* **Patient Demographics:**
    * Age Groups: Adults (30-39 years) formed the largest group (1200 patients), followed by young adults (20-29 years) with 1188 patients.
    * Race Distribution: The largest racial group was White (2571), followed by African American (1951), Multi Racial (1557), and Asian (1060) patients.
* **Admission Status:** Nearly half of the patients (4612) were admitted, while the rest (4604) were treated and released.

####   **Insights:**

* **Identify peak hours and busy days** to optimize staffing and resource allocation.
* **Monitor wait times and satisfaction scores** to improve patient experience.
* **Analyze referral trends** to streamline department workflows and patient flow.
* **Understand patient demographics** to provide tailored care and address health disparities.

##   Technical Details

####   **Tools Used:**

* Power BI (Data Visualization & Analysis)
* DAX & Power Query (Data Transformation)
* SQL (Data Extraction & Processing)

#### **Data Source:**

* The dataset used in this project is available here:  
  📂 [Download Dataset](https://github.com/tanudhaka/Hospital_Emergency_Dashboard/raw/main/Hospital%20ER_Data.csv)


####   **Data Processing:**

* Data cleaning using Power Query.
* Handling missing values & outliers.
* Aggregating data for trend analysis.

## Repository Contents

* 📊 Screenshots of dashboard sections (located in the `screenshots/` folder)
* 📂 Power BI (.pbix) dashboard file
* 📝 README (Project Overview & Instructions)
* 📄 Sample Anonymized Dataset (available via [this link](https://github.com/tanudhaka/Hospital_Emergency_Dashboard/raw/main/Hospital%20ER_Data.csv))

## Screenshots
### Monthly View
![Hospital_emergency_1]![Hospital_emergency_1](https://github.com/user-attachments/assets/c5aaa476-9bfb-4ee6-b755-541fb46a8445)


### Consolidated View
![Hospital_emergency_2]![Hospital_emergency_2](https://github.com/user-attachments/assets/034ccaf8-f276-409e-9b8e-3099abb949ff)


### Patient Details
![Hospital_emergency_3]![Hospital_emergency_3](https://github.com/user-attachments/assets/20d0054b-1240-4615-874f-eb36a2f87501)


### Key Takeaways
![Hospital_emergency_4]![Hospital_emergency_4](https://github.com/user-attachments/assets/3718fd67-1e00-4789-832a-8e3f2a45bcb0)

