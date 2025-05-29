# My-Projects
Link -----> https://drive.google.com/drive/folders/1yYvjP-NMA4tdI536kWzLcpLl9zjfFmWU?usp=sharing

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#**Project-1**


## Customer Churn Prediction – Machine Learning Project

###  Dataset

* **Source**: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* Contains information on demographics, services signed up for, billing, and churn status.

---

###  Tools & Libraries

* **Python** (pandas, numpy, matplotlib, seaborn)
* **EDA**: `ydata-profiling` for automated exploratory data analysis
* **ML Models**: Logistic Regression, Random Forest
* **Metrics**: Accuracy, Confusion Matrix, Classification Report

---

### Project Workflow

1. **Data Ingestion**
   Loaded Telco churn dataset using Pandas.

2. **Automated EDA Pipeline**

   * Used `ydata-profiling` to generate an HTML report.
   * Identified missing values, categorical variables, skewness, and correlation.

3. **Data Preprocessing**

   * Handled null values.
   * Encoded categorical features.
   * Normalized numerical features.
   * Converted churn column into binary target (0 = No, 1 = Yes).

4. **Model Building**

   * Trained a Random Forest Classifier.
   * Achieved **\~85% accuracy**.
   * Visualized feature importance.

5. **Evaluation**

   * Evaluated model using accuracy, precision, recall, and F1-score.

---

### Results

* Model Accuracy: **85%**
* Most important churn indicators: Contract Type, Monthly Charges, Tenure

---

### Outputs

* `telco_churn_eda_report.html`: Auto-generated EDA report
* `churn_model.pkl`: Trained ML model (optional to save)
* Visualizations: Feature importance, confusion matrix

---

###  Key Takeaways

* Early churn detection helps businesses reduce customer loss.
* Automated EDA helps quickly understand data quality and insights.
* Proper preprocessing significantly impacts model performance.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# **Project-2**

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
 
--------------------------------------------------------------------------------------------------

# **Project 3**


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

