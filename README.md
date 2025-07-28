# 📊 Student Performance Analyzer with Pandas

This is a small pandas-based project to analyze student marks stored in a CSV file. It demonstrates the use of powerful pandas indexing and data selection techniques like `.loc`, `.iloc`, `.at`, `.iat`, and `.query`.

## 🚀 Features

- Read and load student data from a CSV file
- Access individual data points using:
  - `loc` – Label-based access
  - `iloc` – Integer-position based access
  - `at` – Fast scalar access using label
  - `iat` – Fast scalar access using integer position
- Calculate average marks of each student
- Filter students who scored an average above 85 using `query`
- Display filtered results

## 🧪 Technologies Used

- Python
- Pandas

## 🗂️ File Structure

students.csv # Sample data file with student names and marks
analysis.py # Main Python file containing all the logic
README.md # This file


## 📥 Sample CSV Format (`students.csv`)


Name,Math,Science,English
Aayush,92,88,91
Bina,76,85,80
Chiran,89,90,95
Dilip,70,65,60


## 📌 Output Example

- Accessed individual values using all four indexing methods
- Calculated and printed each student's average
- Displayed only those students with an average > 85

## ✅ How to Run

1. Clone the repository
2. Ensure `students.csv` is present in the same directory
3. Run the Python script:

```bash
python analysis.py
