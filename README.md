# SGPA Calculation

This repository contains a Python script for calculating **SGPA (Semester Grade Point Average)**. The script processes input data, performs calculations, and outputs the results.

## 📌 Features
- Handles missing data efficiently
- Uses **pandas** and **numpy** for data processing
- Performs SGPA calculations step-by-step
- Outputs results in a structured format

## 🚀 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Gifty04/SGPA_CALCULATION_DS
   cd sgpa-calculation
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:
   ```bash
   python sgpa_calculation.py
   ```

## 📝 Usage

Modify sgpa_calculation.py to input your dataset and adjust parameters as needed.

## ⚠️ Troubleshooting

If you encounter issues while running the script, refer to the common errors below:

KeyError: "['COMM'] not in index"
The column 'COMM' may be missing from your dataset. Check the column names and update the script accordingly.
FileNotFoundError: No such file or directory: 'SEM.csv'
Ensure that the dataset file (data.csv) is present in the correct directory.
ModuleNotFoundError: No module named 'pandas'
Run pip install pandas to install the missing dependency.
ValueError: could not convert string to float
Check for non-numeric values in numeric columns. Ensure proper data cleaning before processing.


## 📌 Notes
- Ensure your dataset is formatted correctly.
- Check the column names in `columns_to_map` before running.

--
