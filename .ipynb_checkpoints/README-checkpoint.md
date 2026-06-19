# LittleSteps Assignment

## Overview

This repository was created to demonstrate GitHub competency as part of the application process for the Data Intern position at Speedoc Pte Ltd.

The project is based on a case study involving **LittleSteps**, an at-home healthcare provider. The objective of the analysis is to clean, process, analyse, and visualize patient visit data to identify patterns in visit durations, nurse travel times, and potential opportunities for improving operational efficiency.

The repository contains the complete workflow, from raw data processing and cleaning to exploratory analysis, visualization, and final business insights.

---

## Repository Structure

The repository is organised into the following folders:

### 1. Datasets

Contains all datasets used throughout the project, including:

* Raw datasets provided for the assignment
* Processed datasets generated during the data cleaning phase
* STTM file to track the attributes in the final dataset

### 2. Data Processing

Contains the notebook:

**DataProcessing_LittleSteps.ipynb**

This notebook performs:

* Initial data exploration
* Data quality assessment
* Data cleaning and preprocessing
* Feature Engineering
* Generation of the final processed dataset used for analysis

The folder also contains the data processing report.

### 3. Data Analysis

Contains the notebook:

**DataAnalysis_LittleSteps.ipynb**

This notebook performs:

* Descriptive statistical analysis
* Operational performance analysis
* Data visualisation
* Business insight generation and recommendations
* plots and analysis_table folders generation

The folder also contains the final report summarising the key findings and recommendations and two additional folders for analysis:

#### 3.1 plots

This folder stores all visualisations generated during the execution of the analysis notebook. Examples include visit duration distributions, service-type comparisons, location-based analyses, nurse travel duration charts, and nurse-note insights. The folder is automatically created when the DataAnalysis_LittleSteps.ipynb notebook is executed and does not need to be downloaded separately.

#### 3.2 analysis_tables

This folder stores summary tables generated during the analysis phase in CSV format. These tables contain aggregated metrics such as service-level summaries, location-level summaries, nurse travel statistics, and keyword impact analyses. The folder is automatically created when the DataAnalysis_LittleSteps.ipynb notebook is executed and does not need to be downloaded separately.

---

## Environment Setup

To run this project on your local machine, ensure that you have one of the following installed:

* Jupyter Notebook
* JupyterLab
* Visual Studio Code (VS Code) with the Python and Jupyter extensions
* Any Python IDE capable of executing Jupyter Notebook (`.ipynb`) files

### Required Libraries

Install all required Python libraries before running the notebooks. If a required library is missing, it can be installed using:

```python
!pip install library_name
```

### Note on Auto-Generated Files

The `plots` and `analysis_tables` folders are generated automatically when the DataAnalysis_LittleSteps.ipynb notebook is executed. Therefore, these folders do not need to be downloaded or manually created when setting up the project on a local machine.

Upon successful execution of the analysis notebook:
- All visualisations will be saved automatically in the `plots` folder.
- All summary and analytical tables will be exported automatically to the `analysis_tables` folder.

Users only need to ensure that the required datasets and notebook files are present in the repository structure.

---

## Project Workflow

### Step 1: Download the Repository

Clone or download the repository and ensure that all folders remain within the same project directory. You need not change the location of the files and datasets in the folders within.

### Step 2: Run the Data Processing Notebook

Open and execute:

```text
Data Processing/DataProcessing_LittleSteps.ipynb
```

This notebook loads the raw dataset, performs data cleaning and preprocessing, and generates the processed dataset into the Datasets folder:

```text
visits_processed.csv
```

Before running the notebook, ensure that the dataset file paths are updated to match the locations on your local system. The code itself looks for the data in the Datasets folder but it is advised to ensure that the file paths are accurate and account for any changes made by the user.

### Step 3: Run the Data Analysis Notebook

Open and execute:

```text
Data Analysis/DataAnalysis_LittleSteps.ipynb
```

This notebook loads the processed dataset and performs the analysis required for the assignment, including visualisations and operational insights.

Before running the notebook, ensure that the processed dataset file path is updated to match the location on your local system. The code itself looks for the data in the Datasets folder but it is advised to ensure that the file paths are accurate and account for any changes made by the user.

### Step 4: Review Final Findings

The final findings, interpretations, and recommendations are documented in the report located within the **Data Analysis** folder.

---

## Key Outputs

The project produces:

* A cleaned and processed dataset
* Summary statistics
* Data visualisations
* A final analytical report (Business insights and recommendations)

---

## Assumptions and Notes

* File paths may need to be updated depending on the user's local directory structure.
* The notebooks are intended to be executed sequentially, starting with the Data Processing notebook followed by the Data Analysis notebook.
* All generated outputs are reproducible by following the workflow described above.
