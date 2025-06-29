# AUTOMATED-REPORT-GENERATION

COMPANY : CODETECH IT SOLUTIONS

NAME : RATHOD KARINA

INTERN ID : CT04DG2833

DOMAIN : PYTHON PROGRAMMIMNG

MENTOR : NEELA SANTOSH

pandas: To read and analyze tabular data (data.csv). fpdf: To generate the PDF file. datetime: To add the current date in the certificate. pd.read_csv("data.csv"): Reads a CSV file containing columns like Name, Department, and Score. groupby("Department"): Groups rows by department. .agg(...): Calculates count, mean, min, and max score for each department. .round(2): Rounds all numerical values to 2 decimal places.Adds a title at the top of every page. cell(0, 10, ...): Adds a text box (width auto-adjusted). align="C": Centers the title. Adds page numbers at the bottom center of every page.Adds a new page with a completion certificate. Displays the intern’s name and internship end date using a multi_cell (multi-line text box).pdf.add_page(): Adds the first page. add_summary_table(): Adds the analysis table. add_certificate(): Adds the certificate to the next page. pdf.output(...): Saves the PDF file.

OUTPUT :

![Image](https://github.com/user-attachments/assets/efb2760a-c624-495c-9b50-2d9723a7464b)
