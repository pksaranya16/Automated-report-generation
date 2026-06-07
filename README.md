# 📄 Automated Report Generation Using Python

## 📌 Project Description

Automated Report Generation is a Python-based project that reads data from a CSV file, performs basic data analysis, and generates a professionally formatted PDF report. This project demonstrates the use of data processing and document generation libraries to automate reporting tasks.

## 🎯 Objectives

* Read data from an external file.
* Analyze and summarize the data.
* Generate a PDF report automatically.
* Present results in a structured and readable format.

## 🛠 Technologies Used

* Python
* Pandas
* FPDF


## 📋 Requirements

Install the required libraries using:

```bash
pip install pandas fpdf
```

## 📊 Input Data

The script reads data from a CSV file named `data.csv`.

### Sample Data

```csv
Name,Score
Alice,85
Bob,90
Charlie,78
David,92
Emma,88
```

## ▶️ How to Run

1. Place `data.csv` in the project folder.
2. Run the Python script:

```bash
python report_generator.py
```

3. The generated PDF report will be saved as:

```text
report.pdf
```

## 📈 Analysis Performed

The script calculates:

* Total number of records
* Average score
* Highest score
* Lowest score

## 📄 Report Contents

The generated PDF report includes:

* Report Title
* Summary Statistics
* Total Records
* Average Score
* Highest Score
* Lowest Score
* Data Table

## 📷 Sample Output

```text
AUTOMATED REPORT GENERATION

Summary Statistics

Total Records : 5
Average Score : 86.60
Highest Score : 92
Lowest Score  : 78
```

## 🚀 Future Enhancements

* Add charts and visualizations.
* Support Excel files.
* Include multiple report formats (PDF, Word).
* Create an interactive dashboard.

## 🎓 Learning Outcomes

Through this project, you will learn:

* File handling in Python
* Data analysis using Pandas
* PDF generation using FPDF
* Automation of reporting workflows

nce and Business Analytics
