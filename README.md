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



