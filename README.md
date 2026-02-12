# Task 1: Data Cleaning and Preprocessing

## Dataset
Original Dataset: `original_dataset.csv`  
Cleaned Dataset: `cleaned_dataset.csv`  

Dataset: **Medical Appointment No Shows**  
Source: Kaggle (or sample dataset)

---

## Objective
Clean and preprocess the raw dataset to make it ready for analysis. This includes handling missing values, duplicates, inconsistent text, date formatting, and data type corrections.

---

## Steps Taken

1. **Missing Values**
   - Filled missing values in `Age` column with median.

2. **Gender Standardization**
   - Converted all entries to lowercase and standardized:
     - `F` → `female`
     - `M` → `male`

3. **Date Formatting**
   - Converted `ScheduledDay` and `AppointmentDay` columns to datetime format.

4. **Duplicates**
   - Removed duplicate rows.

5. **Data Type Corrections**
   - `PatientID` → int
   - `Scholarship`, `Hypertension`, `Diabetes`, `Alcoholism`, `Handcap`, `SMS_received` → int

---

## Tools Used
- Python 3  
- Pandas library  

---

## Files in Repository
- `original_dataset.csv` → Raw dataset  
- `cleaned_dataset.csv` → Cleaned dataset ready for analysis  
- `data_cleaning.py` → Python script for cleaning the dataset  
- `README.md` → This file

---

## Summary
After cleaning, the dataset is structured, consistent, and ready for further analysis or machine learning tasks.
