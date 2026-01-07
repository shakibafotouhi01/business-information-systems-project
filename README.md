# business-information-systems-project
Process mining analysis of Emergency Department (ED) patient flows to identify structural inefficiencies and propose data-driven improvements using Python and PM4Py.

## Project Overview
This project applies process mining techniques to analyze and improve the end-to-end patient treatment process in an Emergency Department (ED). The goal is to discover the actual "AS-IS" process, identify structural inefficiencies like bottlenecks or resource imbalances, and propose a data-driven "TO-BE" model to optimize patient flow.

## Coursework Context
This project was developed as part of the **Business Information Systems** course (A.Y. 2024-2025) at the **University of Milan**.
* **Instructor:** Prof. Paolo Ceravolo
* **Dataset Source:** The event log and patient data used in this analysis were provided by the professor specifically for this coursework.
* **Objective:** To demonstrate the application of the *Knowledge Uplift Trail* methodology in a real-world healthcare scenario using Python and PM4Py.

## Methodology
The analysis follows a structured path to transform raw data into organizational wisdom:
1. **Data Preprocessing:** Cleaning and normalizing vital signs and patient records.
2. **Performance Analysis:** Calculation of KPIs such as Length of Stay (LOS) and Time-to-Treatment.
3. **Process Discovery:** Using Petri Nets and Heuristic Nets to visualize patient paths.
4. **Conformance & Improvement:** Identifying deviations from standard medical procedures and suggesting optimizations.



## Key Findings
* **Resource Imbalance:** Identified that a single administrative nurse handled over 90% of cases, creating a single point of failure.
* **Peak Occupancy:** Data showed critical saturation between 15:00 and 22:00, suggesting a need for staff rescheduling.
* **Bottlenecks:** Significant delays were found between "Triage" and "Medicine Reconciliation" steps.

## Tools
* **Python** (Pandas, Matplotlib, Seaborn)
* **PM4Py** (Process Mining for Python)
