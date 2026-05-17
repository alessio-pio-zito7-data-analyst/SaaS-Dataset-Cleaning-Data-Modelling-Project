# SaaS Dataset Cleaning & Data Modelling Project

## Overview

This project started as a SQL + Power BI analysis using a synthetic SaaS dataset from Kaggle.

During the data ingestion process, I discovered multiple inconsistencies in the original dataset structure, including:
- misleading boolean flags
- duplicated identifiers
- mixed business logic
- formatting and NULL issues
- inconsistent relational modelling

Instead of using the dataset as-is, I redesigned and cleaned the database to create a more reliable and analysis-ready relational model.

---

## What I Did

- Cleaned and restructured the original dataset using Excel
- Redesigned parts of the relational model
- Split inconsistent subscription logic into separate tables
- Performed data ingestion into MySQL using SQL scripts
- Added:
  - Primary Keys
  - Foreign Keys
  - Constraints
  - Validation checks
- Debugged formatting and hidden NULL-related issues
- Created a complete data validation workflow
- Documented the cleaned dataset structure and business logic
- Built a relational data model in Power BI for future BI analysis

---

## Project Structure

Click on the following folders to dive deeper into the core components of the project:

- [Data_Modelling](./Data_Modelling)  
  Excel modelling process, formulas, and raw vs cleaned table comparisons.

- [Data_Ingestion](./Data_Ingestion)  
  SQL ingestion scripts and related screenshots.

- [Debugging_&_Data_Validation](./Debugging_%26_Data_Validation)  
  Debugging and data validation SQL scripts.

- [Raw_&_Processed_SaaS_Dataset](./Raw_%26_Processed_SaaS_Dataset)  
  Raw and cleaned datasets with related documentation.

## Tools Used

- Excel
- MySQL
- Power BI

---

## Goal of the Project

The goal was not to completely reinvent the dataset, but to:
- preserve its original business logic
- fix structural inconsistencies
- improve analytical reliability
- create a BI-ready relational dataset

