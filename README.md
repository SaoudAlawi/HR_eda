# Employee Survey EDA and Analysis

This project performs exploratory data analysis (EDA) on an employee survey dataset. The analysis includes various visualizations created using both Seaborn and Plotly, and an interactive dashboard hosted on Tableau Public.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Overview](#analysis-overview)
- [Interactive Dashboard](#interactive-dashboard)
- [Acknowledgments](#acknowledgments)

---

## Overview

The aim of this project is to uncover insights from an employee survey, exploring factors like job satisfaction, stress levels, workload, sleep hours, and more. The analysis includes both static and interactive visualizations for deeper exploration of the data.

The following steps were performed in the analysis:
- Distribution analysis of key employee characteristics (gender, marital status, etc.).
- Correlation analysis between numerical variables.
- Scatter plots and boxplots to examine relationships between variables such as workload, job satisfaction, team size, and stress levels.

---

## Installation

Follow the instructions below to set up the environment using `pip`.

### Prerequisites
Make sure you have `python3` and `pip` installed.

### Setup

1. Clone the repository or download the project files.

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
3. Install the required packages

Run the following command to install all the necessary dependencies:

```bash
pip install -r requirements.txt
```
## Usage

1. Load the dataset and run the analysis using `eda_analysis.ipynb`.

2. Visualizations include:
   - **Gender Distribution** using Plotly Bar charts.
   - **Marital Status Distribution**.
   - **Workload vs Stress** with an interactive Plotly Scatter Plot.
   - **Correlation Heatmap** of numerical variables.
   - **Team Size vs Job Satisfaction** and more.

---

## Analysis Overview

- **Gender and Marital Status Distributions**: Visualize employee demographics.
- **Workload vs Stress Levels**: Analyze the relationship between workload and stress using Work-Life Balance as a color-coded dimension.
- **Job Satisfaction vs Education**: Compare job satisfaction across different education levels.
- **Correlation Matrix**: Explore correlations between numerical variables like workload, job satisfaction, and team size.
  
These insights provide a comprehensive understanding of the workplace dynamics affecting job satisfaction and stress.

---

## Interactive Dashboard

Explore the full analysis on Tableau Public:  
[Link to the Interactive Tableau Dashboard](https://public.tableau.com/views/employee_analysis_17260344423220/Stressandjobsatisfication?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Acknowledgments

- This analysis was done using a mock employee survey dataset.
