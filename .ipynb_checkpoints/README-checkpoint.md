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

### 3. Data Analysis

Contains the notebook:

**DataAnalysis_LittleSteps.ipynb**

This notebook performs:

* Descriptive statistical analysis
* Operational performance analysis
* Data visualisation
* Business insight generation and recommendations

The folder also contains the final report summarising the key findings and recommendations.

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
