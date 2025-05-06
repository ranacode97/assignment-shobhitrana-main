COMP7024 Programming for Data Science – Assignment Report

Student Information
	•	Name: Shobhit Rana
	•	Student ID: 22076699
	•	Subject Name: Programming for Data Science
	•	Subject Code: COMP7024

Overview

This R Markdown assignment focuses on data wrangling, analysis, and visualization using R. The datasets used simulate real-world healthcare data, covering patient information, clinical conditions, and healthcare encounters. The report answers specific analytical questions using two versions of datasets (PG1 and PG2) to compare COVID-19 cases and common health conditions across demographics and geographies.

Contents

Q1: COVID-19 Analysis

For both PG1 and PG2 datasets:
	•	Merged patient and condition data to analyze COVID-19 occurrences.
	•	Computed average death date for 2020 to estimate age of patients.
	•	Created age groups and analyzed COVID-19 case frequency across age ranges.
	•	Visualized county-level distribution and age-based trends of COVID-19 cases.

Q2: Most Common Symptoms Analysis

For both datasets:
	•	Identified the top 10 most frequent non-COVID-19 conditions.
	•	Compared these symptoms across all patients, male-only, and female-only groups.
	•	Displayed results in tabular form for clear comparison.

Data Files Used
	•	patientsPG1.csv
	•	conditionsPG1.csv
	•	encountersPG1.csv
	•	patientsPG2.csv
	•	conditionsPG2.csv
	•	encountersPG2.csv

Tools & Packages
	•	dplyr, tidyverse, ggplot2: For data manipulation and visualization
	•	base R: For merging datasets and basic analysis

Visualizations
	•	Bar charts depicting:
	•	COVID-19 case distribution by county
	•	COVID-19 case distribution by age group

Key Functions
	•	Custom Age Calculator: Estimated patient age using birth and death dates or a proxy average date for the living.
	•	Group Categorization: Used cut() to bin patients into age ranges.

Declaration

This assignment is original and adheres to academic integrity policies, with no unauthorized collaboration or plagiarism.
