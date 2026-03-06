# Patient Health Data Analysis System

This project is a Python-based data analysis tool designed to clean, process, and categorize patient health records. It focuses on vital signs such as heart rate and body temperature to identify potential health risks.

## Features

* **Data Cleaning:** Removes empty columns and handles "Unnamed" noise in the dataset.
* **Data Transformation:** Converts localized numeric formats (comma to dot) and ensures correct data types for mathematical operations.
* **Missing Value Imputation:** Automatically fills missing age data using the median value of the dataset to maintain statistical integrity.
* **Automated Medical Categorization:**
    * **Heart Rate:** Classifies patients into Bradycardia (<60 BPM), Normal, and Tachycardia (>100 BPM).
    * **Temperature:** Identifies Hypothermia (<36°C), Normal, and Hyperthermia (>38°C).
* **Risk Reporting:** Generates a diagnosis-based summary for patients identified with hyperthermia.

## Requirements

To run this project, you need:
* Python 3.x
* Pandas library

## How to Run

1. Ensure `patients_datas.csv` is in the same directory as the script.
2. Run the Jupyter Notebook or Python script.
3. The system will output the processed dataframes and a summary risk report.

## Dataset

The dataset (`patients_datas.csv`) includes information such as:
* Patient ID, Age, Diagnosis, Temperature, Heart Rate, and Length of Stay.



## Disclaimer
This software is a prototype for data analysis and visualization. It does not provide clinical diagnosis or medical recommendations. The insights generated are intended to demonstrate data processing capabilities, not to replace professional medical judgment.
