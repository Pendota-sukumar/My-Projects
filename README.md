# My-Projects
Link -----> https://drive.google.com/drive/folders/1yYvjP-NMA4tdI536kWzLcpLl9zjfFmWU?usp=sharing

# Data Workflow Automation using Python & GenAI

This project demonstrates how to **automate data cleaning tasks** using Python and generate insightful **natural language summaries and dashboards** using **GenAI** and **Plotly visualizations**. It integrates Together AI’s LLaMA-3 model to generate human-like summaries and uses Plotly to build dashboards that can be embedded on web platforms like GitHub Pages.

---

##  Features

- ✅ **Automated Data Cleaning** using Python
- 🤖 **GenAI Report Generation** using Together AI (LLaMA-3)
- 📈 **Interactive Visual Dashboards** using Plotly
- 🌐 **HTML Report Viewable on GitHub & Google Colab**
- 📂 Modular Codebase for Reusability

---

##  Project Workflow

### 1️⃣ Data Preparation
- Load and optionally clean source CSV data.
- Reusable Python functions are used to clean or filter future datasets.

### 2️⃣ GenAI Report Generation
- Use Together AI’s LLaMA-3 via API to generate:
  - Natural language summaries
  - Haikus (fun test)
  - Insights from data
- Prompt is customizable to reflect your dataset.

### 3️⃣ Visualization & Reporting
- Generate a Plotly dashboard with:
  - Bar Charts
  - Line Graphs
  - Pie Charts
- Exported as an `.html` file to be:
  - Embedded in Google Colab
  - Hosted on GitHub Pages
 
--------------------------------------------------------------

## **Project 2**


## **Project Summary: Automated Production Defect Dashboard using Excel & Tableau**

### **Objective:**

To build an automated and interactive Tableau dashboard that visualizes production defects and helps identify performance issues across different time periods, product lines, and shifts using data from a dynamic Excel file.

---

###  **Data Source:**

* **Excel file** containing:

  * Date of Inspection
  * Product Line
  * Shift (A/B/C)
  * Total Units Inspected
  * Total Defective Units

---

###  **Key Features & Metrics:**

1. **Defect Rate Calculation:**

   * Formula: `(Defects / Total Inspected) × 100`
   * Created as a **calculated field** in Tableau.

2. **Interactive Charts Developed:**

   *  **Defect Trend Over Time** (Line Chart)

     * Shows how defect rate changes daily or monthly.
   * **Defect Rate by Shift** (Bar Chart)

     * Compares defect rates across Shift A, B, and C.
   *  **Defect Rate by Product Line** (Bar or Tree Map)

     * Highlights which product lines have higher defects.

3. **Filters Added:**

   * Date Range Selector
   * Shift Filter
   * Product Line Filter

4. **Tooltips and Labels:**

   * Dynamic percentages shown in all visualizations.
   * Enhanced user interaction with visual tooltips.

---

### **Automation Setup:**

* Tableau is connected to the Excel file such that any update to the Excel data:

  * Automatically reflects in Tableau upon data refresh.
  * No manual re-import or rework required.

---

###  **Business Impact:**

* Enables production teams and quality engineers to:

  * Monitor real-time defect trends.
  * Identify problematic shifts or product lines.
  * Make quick decisions for process improvements.

--------------------------------------------------------------------------------------------------

##**Project 3**


##  Manufacturing Sensor Dashboard – Tableau Project

###  Project Summary

This project presents an interactive **Tableau dashboard** designed to monitor and analyze machine sensor data from a manufacturing unit. The dataset includes time-stamped records of sensor readings, machine status, quality checks, and product counts.

The dashboard helps track operational efficiency, identify abnormal sensor readings, and support quality control decisions.

---

###  Key Features

* **Sensor Reading Trend:** Time-series analysis of sensor values.
* **Machine Status Breakdown:** Visual representation of machines in *On*, *Standby*, and *Off* states.
* **Product Count Monitoring:** Total and average product count over time.
* **Quality Check Analysis:** Percentage of products passing/failing quality checks.
* **Reference Lines:** Added visual indicators for normal sensor range (e.g., 20 to 70) to quickly spot anomalies.
* **Interactive Filters:** Drill down by date, machine status, and quality check.

---

### 📁 Dataset Overview

| Column          | Description                                    |
| --------------- | ---------------------------------------------- |
| `ID`            | Unique identifier for each record              |
| `Timestamp`     | Date and time of data capture                  |
| `SensorReading` | Numeric sensor value recorded from the machine |
| `MachineStatus` | Operational status: On, Off, or Standby        |
| `QualityCheck`  | Boolean value indicating pass/fail of QC       |
| `ProductCount`  | Number of products processed at that timestamp |

---

###  Tools Used

* **Tableau Desktop** for visualization
* **Microsoft Excel / CSV** for data import and preprocessing

---

###  Insights

* Machines in `Standby` state tend to show lower sensor readings.
* Quality check failures correlate with low or extremely high sensor readings.
* Identified optimal sensor operating range to reduce QC failures.

---

###  Use Cases

* Predictive maintenance based on abnormal sensor trends.
* Root cause analysis of failed quality checks.
* Production planning and resource allocation using product count metrics.

