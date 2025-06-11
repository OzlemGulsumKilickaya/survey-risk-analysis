
# 🏥 Healthcare Business Continuity Survey Analysis

This repository contains the full workflow for analyzing survey data related to healthcare business continuity management. The project involves statistical exploration of participant responses collected via structured questionnaires. Analysis is performed using **R** within a **Jupyter Notebook**, and results are summarized in an accompanying report.

## 📦 Contents
project-root/
├── data/
│ ├── raw_survey_data.xlsx
│ ├── survey_data_by_question.xlsx
│
├── notebooks/
│ └── R_Codes_Results.ipynb # Jupyter Notebook with R analysis
│
├── reports/
│ └── Statistical_Analysis_Report.docx
│
├── README.md
├── .gitignore
└── LICENSE



## 📊 Project Scope

- **Goal**: To understand patterns and risks in healthcare organizations' continuity planning
- **Data**: Collected through structured survey questionnaires targeting key domains of continuity
- **Tools**:
  - R (within Jupyter using IRKernel)
  - `tidyverse`, `readxl`, `psych`, and other R libraries
- **Outputs**:
  - Cleaned data tables
  - Summary statistics and visualizations
  - Reported insights for each question domain

## 🧪 Analysis Workflow

1. **Data Import & Cleaning**  
   Import `.xlsx` files using `readxl` and preprocess for analysis.

2. **Exploratory Analysis**  
   Summary tables, mean/median scores by question/domain.

3. **Statistical Testing** *(if applicable)*  
   Apply group comparisons or correlation analysis to explore significant patterns.

4. **Visualization**  
   Use plots to convey trends across departments, roles, or response types.

5. **Reporting**  
   Findings are consolidated in a DOCX report for decision-making or publication.

## 🔧 How to Run

1. Launch Jupyter Notebook with R kernel:
   ```bash
   jupyter notebook

