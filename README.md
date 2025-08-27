# Clinical Data Analysis Portfolio Project

This repository demonstrates a **mock Phase II clinical trial data analysis**, showcasing skills relevant to **Customer Success Engineering** and clinical data management.

## Project Contents
- **clinical_trial_mock_data.csv** – Simulated dataset (Treatment vs Placebo group, demographics, outcomes, adverse events).  
- **Clinical_Data_Analysis_Notebook.ipynb** – Python notebook with full data cleaning, validation, statistical analysis, and visualizations.  
- **Clinical_Data_Validation_Report.pdf** – Professional-style PDF report summarizing data quality checks, validation tables, and visualizations.

## Key Features
- Data cleaning and validation following **EDC-style edit checks**:
  - Missing severity
  - Logical inconsistencies (e.g., male pregnancy)
  - Invalid age or outcome values
- Adverse event analysis by treatment arm
- Statistical analysis and exploratory data visualization
- Generation of professional report deliverable (PDF)

## Tools & Libraries
- Python: pandas, numpy, matplotlib, seaborn
- PDF report: reportlab
- Jupyter/Colab for interactive analysis

## Relevance to DAta Analyst Role
This project simulates tasks you would perform in supporting clinical trials with a **CDMS/EDC platform**, including:  
- Implementing and validating study protocols  
- Ensuring data quality and auditability  
- Communicating findings to clients in professional reports  
- Providing actionable recommendations for data management  

## How to Use
1. Open the notebook `Clinical_Data_Analysis_Notebook.ipynb` in Google Colab.  
2. The dataset is loaded directly from GitHub:  
   ```python
   url = "https://raw.githubusercontent.com/thaise-steffani/Clinical-Data-Analysis-Portfolio-Project/main/clinical_trial_mock_data.csv"
   df = pd.read_csv(url)
