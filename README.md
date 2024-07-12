# Attendance Gap Finder

Attendance Gap Finder is a Streamlit web application that highlights differences between two datasets (main and duplicate) provided by the user. It uses Pandas for data manipulation and Openpyxl for Excel file handling to identify and visually highlight discrepancies in the main dataset compared to the duplicate dataset.

## Features

- Upload main and duplicate datasets in either Excel (.xlsx) or CSV (.csv) formats.
- Automatically identifies rows with missing or differing data between the main and duplicate datasets.
- Outputs a new Excel file with highlighted discrepancies for easy review and analysis.
- Provides interactive data visualization using Streamlit to display the main and duplicate datasets.

## Installation

To run this application locally, ensure you have Python installed. Clone this repository and install the required dependencies:

```bash
git clone https://github.com/kavinandan18/attendance-gap-finder.git
cd attendance-gap-finder
