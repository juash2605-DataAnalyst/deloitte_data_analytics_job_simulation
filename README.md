# Deloitte Australia – Data Analytics Job Simulation (Forage)

📌 Project Overview

This project was completed as part of the **Deloitte Australia Data Analytics Virtual Experience Program** on Forage.

The simulation focused on solving two business problems using **Tableau** and **Microsoft Excel**. The objective was to analyze operational data, create interactive dashboards, and apply logical business rules to support data-driven decision-making.


🛠️ Tools & Technologies

* Tableau Public
* Microsoft Excel
* JSON
* Data Visualization
* Business Intelligence


📊 Task 1 – Machine Downtime Analysis

## Business Problem

Daikibo Industrials wanted to identify which manufacturing factory experienced the highest machine downtime and determine which machine type contributed most to the downtime.

## Dataset

* Industrial telemetry dataset (JSON)
* Machine status records collected from multiple factories

## Approach

* Imported JSON data into Tableau.
* Created a calculated field to measure downtime.
* Built an interactive dashboard showing downtime by factory and device type.
* Added dashboard filtering to allow drill-down analysis.

### Calculated Field

```text
IF [Status] = "unhealthy" THEN 10
ELSE 0
END
```

Each unhealthy machine record represents **10 minutes** of downtime.

## Dashboard Features

* Downtime by Factory
* Downtime by Device Type
* Interactive dashboard filtering
* Comparative bar charts

## Key Findings

* Factory with the highest downtime:

  * ** Daikibo Factory Seiko **

* Device type with the highest downtime:

  * ** LaserWelder  **

---

 📈 Task 2 – Gender Pay Equality Analysis

## Business Problem

Deloitte's Forensic Technology team investigated gender pay equality across different job roles. The objective was to classify equality scores based on predefined business rules.

## Tool Used

* Microsoft Excel

## Business Rules

| Equality Score                   | Classification        |
| -------------------------------- | --------------------- |
| -10 to 10                        | Fair                  |
| -20 to -11 or 11 to 20           | Unfair                |
| Less than -20 or Greater than 20 | Highly Discriminative |

## Excel Formula

Used nested logical functions including:

* IF()
* AND()
* OR()

to automatically classify every employee record.

---

📂 Repository Structure

```text
deloitte-data-analytics-job-simulation/
│
├── data/
├── tableau/
├── screenshots/
├── certificate/
└── README.md
```

---

💡 Skills Demonstrated

* Data Analysis
* Tableau Dashboard Development
* Data Visualization
* Business Intelligence
* Dashboard Filtering
* Excel Logical Functions
* Business Problem Solving
* Data Interpretation

---


