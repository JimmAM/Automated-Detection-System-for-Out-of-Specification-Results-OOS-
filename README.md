# Automated Out of Specification (OOS) Detection System

## Project Description
This project develops an automated Python-based solution for the Quality Control (QC) department. Its primary objective is to process raw analytical data (e.g., from HPLC runs), automatically detect Out of Specification (OOS) results, and generate immediate alerts to trigger Corrective and Preventive Actions (CAPA).

In highly regulated pharmaceutical environments, manual review of large datasets is susceptible to human error and fatigue. This script ensures strict adherence to Data Integrity principles (ALCOA+), standardizing the validation workflow and significantly reducing review turnaround times.

## Objectives
* **Data Cleaning & Preprocessing:** Identify and resolve null values, data entry anomalies, and statistical outliers within QC records.
* **Logical Validation:** Enforce Lower and Upper Specification Limits (LSL / USL) across manufactured batches.
* **Traceability & Compliance:** Generate a secure, auditable final report detailing the disposition (Pass/Fail) of each evaluated batch.

## Tools & Technologies
* **Language:** Python 3
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib (for process trend charts and control limit visualization)

## Data Structure
The analysis utilizes a dataset (simulated to maintain confidentiality) comprising the following variables:
* `Sample_ID`: Unique traceability identifier.
* `Batch`: Production batch or lot number.
* `Analysis_Date`: Timestamp of the analytical run.
* `Concentration_Percentage`: Quantitative assay result of the Active Pharmaceutical Ingredient (API).
* `Analyst`: Personnel responsible for the assay execution.

## Business Value
Implementing this automated pipeline reduces the operational burden on laboratory analysts and mitigates the compliance risk associated with releasing batches containing undetected quality deviations.
