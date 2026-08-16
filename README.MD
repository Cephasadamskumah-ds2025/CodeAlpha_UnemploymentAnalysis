# CodeAlpha Task 2: Unemployment Analysis with Python

## Overview

This project was completed as part of the **CodeAlpha Data Science Internship**.

The objective is to analyze unemployment trends in India using Python to uncover patterns across regions, months, and the COVID-19 period. Through exploratory data analysis (EDA), the project provides insights into changes in unemployment rates, labour participation, and estimated employment.

---

## Project Objectives

- Analyze unemployment trends across different states and regions.
- Examine the impact of COVID-19 on unemployment.
- Compare employment levels before and during the pandemic.
- Explore labour force participation and its relationship with unemployment.
- Identify seasonal and monthly unemployment patterns.
- Generate meaningful visualizations to support data-driven insights.

---

## Dataset

This project uses the **Unemployment in India** dataset containing labour market statistics across different regions in India.

The repository includes:

- **Unemployment in India.csv** – Original dataset.
- **cleaned_unemployment_data.csv** – Cleaned dataset after preprocessing, including handling missing values, formatting columns, and preparing the data for exploratory data analysis.

The dataset includes the following features:

- Region
- Date
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area (Urban/Rural)

## Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset overview
- Missing value analysis
- Duplicate value check
- Data type inspection
- Descriptive statistics
- Unemployment distribution
- Regional unemployment comparison
- Labour participation analysis
- Correlation analysis
- Monthly unemployment trends
- COVID-19 impact analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---


## Project Structure

```
├── unemployment_analysis.ipynb
├── Unemployment in India.csv          # Original dataset
├── cleaned_unemployment_data.csv       # Cleaned dataset 
├── README.md
└── requirements.txt
```

---

## Key Insights

- COVID-19 significantly increased unemployment rates.
- Employment levels declined during the pandemic.
- Some regions experienced considerably higher unemployment than others.
- Labour participation varied across states and showed a weak relationship with unemployment.
- Monthly analysis revealed noticeable seasonal changes.

---

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/Cephasadamskumah-ds2025/CodeAlpha_UnemploymentAnalysis.git
```

2. Navigate into the project.

```bash
cd unemployment-analysis
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the notebook and run all cells.

---

## Author

**Cephas Adams Kumah**

 Data Scientist | Licensed Medical Laboratory Scientist

---

## Internship

**Organization:** CodeAlpha

**Program:** Data Science Internship

**Task:** Task 2 – Unemployment Analysis with Python