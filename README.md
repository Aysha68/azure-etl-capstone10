# End-to-End Azure ETL Capstone Project

## Project Overview

This project demonstrates an end-to-end ETL (Extract, Transform, Load) data engineering pipeline using Microsoft Azure.

The project uses student performance data and processes the data through Azure Storage and Azure Data Factory. The cleaned and transformed data is then used to create a Power BI dashboard for analysis and visualization.

## Project Objectives

- Build an end-to-end ETL pipeline using Azure.
- Store raw data in Azure Blob Storage.
- Use Azure Data Factory to orchestrate the ETL process.
- Clean and transform student performance data.
- Store the curated data for analysis.
- Create a Power BI dashboard.
- Document the complete data engineering workflow.

## Technologies Used

- Microsoft Azure
- Azure Blob Storage
- Azure Data Factory
- Power BI
- GitHub
- CSV
- Data Transformation / ETL

## Data Pipeline

The project follows this workflow:

```text
Raw Student Data
       ↓
Azure Blob Storage
       ↓
Azure Data Factory
       ↓
Data Cleaning & Transformation
       ↓
Curated Student Data
       ↓
Power BI Dashboard
```
## Dataset

The dataset contains student performance information such as:

- Student ID
- Gender
- Age
- Study Hours
- Attendance
- Assignment Score
- Midterm Score
- Final Score
- Passed
- Performance Level

The original raw dataset is stored in the `data/raw` folder.

## ETL Process

### 1. Extract

The original student dataset was collected and stored as a CSV file. The raw data was uploaded to Azure Blob Storage for processing.

### 2. Transform

Azure Data Factory was used to clean and transform the student data.

The transformation process included data cleaning, filtering, and creating derived information required for analysis.

### 3. Load

The transformed dataset was saved as curated data and used for reporting and visualization.

The curated dataset is stored in the `data/curated` folder.

## Power BI Dashboard

Power BI was used to visualize the transformed student data.

The dashboard provides insights into student performance, attendance, study hours, scores, passing results, and performance levels.

## Repository Structure

```text
azure-etl-capstone10/
│
├── data/
│   ├── raw/
│   │   └── 1student_data.csv
│   │
│   └── curated/
│       └── azure project file cleaned.csv
│
├── docs/
│   └── project-documentation.md
│
├── screenshots/
│   └── .gitkeep
│
└── README.md
```
## Project Outcome

The project demonstrates how raw student data can be transformed into useful analytical information using an Azure-based ETL pipeline.

The final curated data was connected to Power BI to create visualizations and support analysis of student performance.

## Author

**Aysha68**

Data Engineering / Diploma Program

