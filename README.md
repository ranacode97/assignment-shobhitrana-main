COMP7024 Assignment - Programming for Data Science

Student Name: Shobhit Rana
Student ID: 22076699
Subject: Programming for Data Science (COMP7024)
University: Western Sydney University

Overview

This assignment focuses on analyzing two synthetic healthcare datasets (PG1 and PG2) using R. The analysis involves merging datasets, data cleaning, deriving new variables (like age and age groups), and visualizing patterns in COVID-19 patient data.

Key R libraries used:
	•	ggplot2
	•	dplyr
	•	tidyverse

Datasets
	•	patientsPG1.csv, patientsPG2.csv
	•	conditionsPG1.csv, conditionsPG2.csv
	•	encountersPG1.csv, encountersPG2.csv

Tasks Performed

Q1: COVID-19 Patient Analysis
	•	Merged patient and condition datasets.
	•	Calculated age using BIRTHDATE and DEATHDATE.
	•	Identified and visualized COVID-19 and suspected COVID-19 cases by:
	•	County distribution (bar plots)
	•	Age group distribution (0–18, 19–35, 36–50, 51+)

Q2: Most Frequent Symptoms (Non-COVID)
	•	Generated frequency tables of medical conditions.
	•	Filtered out COVID-19 related cases.
	•	Extracted top 10 most common conditions:
	•	For all patients
	•	Separately for males and females

📁 Folder Structure

.
├── patientsPG1.csv
├── patientsPG2.csv
├── conditionsPG1.csv
├── conditionsPG2.csv
├── encountersPG1.csv
├── encountersPG2.csv
├── 22076699_Assignment.Rmd
├── 22076699_Assignment.pdf
└── README.md

Declaration

This work is original and complies with Western Sydney University’s academic integrity policies. No unauthorized collaboration or copying was involved.
