# Automated-Financial-Statement-PDF-Generation
# Overview
The Financial Statements PDF Generator is a Python-based tool designed to fetch financial data from an API and generate detailed PDF reports. These reports include tables and graphs showcasing trends in financial metrics such as EPS, EBITDA, and Gross Profit over the past five years. This tool is useful for financial analysts, accountants, and other professionals who need to create comprehensive and well-formatted financial reports.

# Features
Fetches financial statements data from a provided API.
Generates a PDF report with:
A header containing the company’s name.
A table detailing financial metrics including calendar year, period, revenue, gross profit, EBITDA, EBITDA ratio, and EPS.
Three graphs showing trends for EPS, EBITDA, and Gross Profit over the past five years.
Clean and neat formatting with detailed axis and data labels on charts.
Contact information (name, phone number, email) included at the bottom right corner of the last page, within a square box.

# Technologies Used
Python: Programming language used for the development of the script.
Pandas: For data manipulation and cleaning.
SQL: Database used to store and query financial data.
SqlAlchemy: Python SQL Toolkit for database access.
Pyodbc: Module for exporting data to SQL Server.
ReportLab: Library used for generating PDF documents.
Matplotlib: Library for creating visualizations and graphs.
