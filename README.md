# 📊 Power BI Portfolio: Data Industry Intelligence

Welcome to my central Power BI portfolio repository. This space organizes specialized dashboards engineered to analyze the global data job market. The projects focus on end-to-end analytics pipelines, including programmatic ETL with Power Query, star schema data modeling, and robust DAX configurations.

---

## 🚀 Projects Overview

Explore the specific dashboards integrated within this repository below. Click on each project title to view its full interactive documentation, operational demos, and architecture.

### 1. [Global Data Jobs Dashboard (Dark Mode)](./global-datajobs-dashboard/)
* **Description:** A high-impact executive interface dedicated to isolating critical market skillsets and financial benchmarks across global data sectors.
* **Core Metrics:** Features deep-dives into 479K postings tracking a metric of **4.8 average skills per job**, mapping Python and SQL as baseline dependencies.
* **Key Visuals:** Parameterized toggle switch for viewing metrics by "Job Percent" vs. "Job Count", and salary metrics via "Median Yearly Salary" vs. "Median Hourly Salary".

### 2. [Data Jobs Dashboard (Light Mode)](./datajobs-dashboard/)
* **Description:** An analytical dashboard tracking high-level recruitment trends, rating systems, and job distribution over time.
* **Core Metrics:** Maps career metrics such as dynamic **Job Title Drill Through pages** (e.g., Data Engineer pipelines tracking 89% contractor ratios and global geographical job maps).
* **Key Visuals:** Granular timeline sliders tracking macro hiring dips and spikes, combined with scatter plot comparisons evaluating Hourly vs. Median Salaries across tech fields.

---

## 🛠️ Core Engineering Demonstrated

* **Data Architecture:** Structuring highly responsive **Star Schemas** by extracting wide-form datasets into optimized relational tables (`fact_tables`, `date_dim`, `skills_dim`).
* **Advanced Calculation Layers (DAX):** Writing performant measures to capture dynamically changing median salaries (\$113K benchmark), hourly metrics (\$47.62–\$48), and running totals.
* **ETL & Data Wrangling:** Comprehensive data cleaning operations utilizing **Power Query** to strip anomalies, map null values, and structure relational keys.
* **User Interface & UX Optimization:** Implementing advanced navigation mechanics, sync-slicers, context-aware drill-through pages, and responsive cross-filtering.

---

## 📂 Repository Layout

```text
├── datajobs-dashboard/             # Project 1: Macro Data Jobs Tracker
│   ├── images/                     # System screenshots and views
│   └── datajobs_dashboard.pbix     # Power BI report file
│
├── global-datajobs-dashboard/      # Project 2: Competency & Income Analyzer
│   ├── images/                     # Screenshot assets and demo animations
│   └── global_datajobs_dashboard.pbix # Power BI report file
│
└── README.md                       # Portfolio master index landing page
```
