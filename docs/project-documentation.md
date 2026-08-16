# Project Documentation

## 1. Project Overview

This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline using Microsoft Azure.

The project uses student performance data. The data is stored, processed, cleaned, transformed, and prepared for analysis using Azure Blob Storage and Azure Data Factory. The final curated data is visualized using Power BI.

## 2. Project Architecture

The project follows this workflow:

Student Raw Data
       ↓
Azure Blob Storage
       ↓
Azure Data Factory
       ↓
Data Cleaning and Transformation
       ↓
Curated Student Data
       ↓
Power BI Dashboard

## 3. Dataset

The project uses student performance data containing information such as:

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

The raw dataset is stored in the GitHub repository under:

`data/raw/1student_data.csv`

The curated dataset is stored under:

`data/curated/azure project file cleaned.csv`

## 4. Azure Blob Storage

Azure Blob Storage was used to store the project data during the ETL process.

The raw student data was uploaded to an Azure Storage container before being processed by Azure Data Factory.

The Azure Storage screenshots are available in the `screenshots` folder.

## 5. Azure Data Factory

Azure Data Factory was used to create and execute the ETL pipeline.

The pipeline was used to move the student data through the transformation process.

The data flow included data cleaning, filtering, and transformation activities before producing the curated dataset.

## 6. Data Transformation

The student data was transformed to prepare it for analysis.

The transformation process included:

- Cleaning the source data
- Filtering records
- Creating derived information
- Preparing the final curated dataset
- Writing the transformed data to the output location

The final transformed data was saved as:

`azure project file cleaned.csv`

## 7. Power BI Dashboard

Power BI was used to create visualizations from the curated student data.

The dashboard provides insights into:

- Student performance
- Attendance
- Study hours
- Assignment scores
- Midterm scores
- Final scores
- Passing results
- Performance levels

A screenshot of the Power BI dashboard is available in the `screenshots` folder.

## 8. GitHub Repository Structure

The repository is organized as follows:

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
│   ├── azure blob storage.png
│   ├── blob storage.png
│   ├── containers.png
│   ├── curated data.png
│   ├── Data fatctory validated.png
│   ├── data flow 1.png
│   ├── Debug process.png
│   ├── Sink1.png
│   └── power-bi-dashboard.png.png
│
└── README.md

## 9. Project Outcome

The project demonstrates the complete process of taking raw student data and transforming it into curated data suitable for analysis.

Azure Blob Storage was used for data storage, Azure Data Factory was used for ETL processing, and Power BI was used for visualization.

The project provides an end-to-end example of a cloud-based data engineering workflow.

## 10. Technologies Used

- Microsoft Azure
- Azure Blob Storage
- Azure Data Factory
- Power BI
- GitHub
- CSV
- ETL / Data Transformation

## 11. Author

**Aysha68**

Data Engineering / Diploma Program
