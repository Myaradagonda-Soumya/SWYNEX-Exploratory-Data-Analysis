# SWYNEX Exploratory Data Analysis

## Task 2 – Exploratory Data Analysis

This project is part of my internship with **SWYNEX Technologies**.

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on the cleaned dataset prepared during Task 1. The analysis focuses on understanding the data, calculating important statistics, identifying trends and patterns, detecting anomalies, and presenting meaningful insights through visualizations.

---

## 📌 Objectives

* Understand the structure of the cleaned dataset
* Analyze numerical and categorical variables
* Calculate descriptive statistics
* Identify trends and patterns
* Detect possible outliers and anomalies
* Analyze relationships between variables
* Create meaningful data visualizations
* Extract at least five useful insights from the dataset

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## 📂 Dataset

The project uses the cleaned dataset generated during **Task 1 – Data Cleaning and Preparation**.

Dataset file:

```text
data/
└── cleaned_dataset.csv
```

The cleaned dataset is used as the primary source for all analysis performed in this task.

---

## 🔍 EDA Performed

The following exploratory analysis was performed:

### 1. Dataset Overview

* Number of rows and columns
* Column names
* Data types
* Basic dataset structure

### 2. Data Quality Check

* Missing-value analysis
* Duplicate-value analysis
* Identification of potential anomalies
* Validation of data types

### 3. Descriptive Statistics

Calculated important statistics such as:

* Mean
* Median
* Standard deviation
* Minimum
* Maximum
* Quartiles

### 4. Categorical Analysis

Analyzed categorical variables such as:

* Department
* Region
* Employee Status
* Performance Score
* Remote Work

### 5. Salary Analysis

Explored:

* Salary distribution
* Average salary
* Salary variation
* Average salary by department
* Salary differences across performance categories

### 6. Employee Analysis

Analyzed:

* Age distribution
* Department-wise employee count
* Region-wise employee count
* Employee performance distribution

### 7. Remote Work Analysis

Compared:

* Remote employees
* On-site employees

### 8. Joining Trend Analysis

Analyzed employee joining trends over different years to identify changes in employee recruitment.

### 9. Correlation Analysis

Used correlation analysis and a heatmap to understand relationships between numerical variables.

### 10. Outlier Analysis

Used box plots to identify potential outliers in numerical variables such as age and salary.

---

## 📊 Visualizations

The following visualizations were created:

* Employee Distribution by Department
* Employee Distribution by Region
* Salary Distribution
* Performance Score Distribution
* Remote Work Distribution
* Average Salary by Department
* Average Salary by Performance Score
* Age Distribution
* Employee Joining Trend
* Correlation Heatmap
* Outlier Detection using Box Plots

All important charts are stored in:

```text
visualizations/
```

---

## 💡 Key Insights

The analysis identified several useful insights from the dataset:

1. Employee distribution varies across different departments, with some departments having considerably more employees than others.

2. Employee representation differs across regions, indicating variations in the geographical distribution of the workforce.

3. The performance analysis shows that some performance categories contain a larger proportion of employees than others.

4. Average salary varies across departments, indicating differences in compensation levels between departments.

5. Salary values also differ across performance categories, showing an observed relationship between performance level and salary in the dataset.

6. The remote-work analysis shows the proportion of employees working remotely compared with employees working on-site.

7. Employee joining trends reveal variations in the number of employees joining during different years.

8. Correlation analysis helps identify relationships between numerical variables such as age and salary.

9. Outlier analysis helps identify unusual values that may require further investigation.

10. The EDA also helped identify potential data-quality issues that should be validated before using the data for further analysis.

---

## 📁 Project Structure

```text
SWYNEX-Exploratory-Data-Analysis/
│
├── data/
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── visualizations/
│   ├── department.png
│   ├── region.png
│   ├── salary_distribution.png
│   ├── performance.png
│   ├── remote_work.png
│   ├── salary_department.png
│   ├── salary_performance.png
│   ├── age_distribution.png
│   ├── joining_trend.png
│   └── correlation_heatmap.png
│
├── README.md
│
└── requirements.txt
```

---

## ▶️ How to Run the Project

### Step 1 – Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/SWYNEX-Exploratory-Data-Analysis.git
```

### Step 2 – Navigate to the project

```bash
cd SWYNEX-Exploratory-Data-Analysis
```

### Step 3 – Install required libraries

```bash
pip install -r requirements.txt
```

### Step 4 – Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5 – Open the notebook

Open:

```text
notebooks/EDA.ipynb
```

Run the cells sequentially to reproduce the analysis and visualizations.

---

## 📦 Requirements

The project requires:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 📈 Outcome

This project demonstrates practical skills in:

* Data Exploration
* Data Analysis
* Statistical Analysis
* Data Visualization
* Pattern Identification
* Anomaly Detection
* Python Programming
* Business Insight Generation

The analysis transforms the cleaned dataset into meaningful information that can support further data-driven analysis.
