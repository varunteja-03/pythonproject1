# pythonproject1
Excel Transaction Automation using Python
Project Description:
This project automates the process of handling Excel transaction data by applying a discount calculation using Python. It reads data from an input Excel file, processes each transaction, and writes the updated values into a new file.

The goal is to reduce manual effort, improve accuracy, and demonstrate practical automation using Python.

Features:
Reads data from Excel file
Applies automatic discount calculation (10%)
Updates processed data into a new column
Saves results into a new Excel file
Fast and efficient data processing

Tech Stack
Language: Python
Library: openpyxl

Project Structure:
automationproject/
│
├── main.py                # Python script
├── transactions.xlsx      # Input dataset
├── transactions2.xlsx     # Output file (generated)
└── README.md

How It Works
Load Excel file using openpyxl
Access active worksheet
Iterate through rows of transaction data
Calculate discounted value (10%)
Store updated value in a new column
Save results to a new Excel file

How to Run:
1.Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2.Install Requirements
pip install openpyxl
3.Run the Script
python main.py

Use Cases:
Automating Excel-based financial calculations
Processing bulk transaction data
Reducing manual spreadsheet work
