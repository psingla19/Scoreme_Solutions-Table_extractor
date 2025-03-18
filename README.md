# Scoreme_Solutions-Table_extractor

#Overview
This tool is designed to detect and extract tables from system-generated PDFs and save them into Excel files. The tool does not rely on borders or visual cues to detect tables; instead, it uses text alignment and spacing to identify and extract tabular data. It is particularly useful for PDFs with irregular or borderless tables.

#Features
Table Detection: Detects tables based on text alignment and spacing.

Borderless Table Support: Works with tables that do not have visible borders.

Excel Export: Saves extracted tables into Excel files, with each table on a separate sheet.

Illegal Character Handling: Removes non-printable and control characters to ensure compatibility with Excel.



#Workflow Model
1. Input PDF:

The user provides a PDF file containing tables (with or without borders).

2. PDF Processing:

The tool reads the PDF and extracts text blocks with their positions.

3. Table Detection:

The tool identifies tables by grouping text blocks into rows and columns based on their alignment.

4. Table Extraction:

The tool extracts the content of detected tables and cleans the text to remove illegal characters.

5. Excel Export:

The extracted tables are saved into an Excel file, with each table on a separate sheet.

#Output:

The user receives an Excel file containing the extracted tables.



#Limitations
The tool may not work well with PDFs that have complex layouts or overlapping text.

Tables with merged cells or irregular spacing may not be extracted accurately.

#Future Improvements
Add support for merged cells.

Improve table detection for complex layouts.

Add a GUI for easier use.

Contact
For questions or issues, please contact:
Your Name - Pratham Singla
Your Email - psingla_be21@thapar.edu
