# Data Quality Checker

This project is a small Python script I built to practice data validation like a data engineer. It checks through a list of records to find missing names, bad emails, or negative sales numbers. Each record is tested with a function, and depending on the results, it’s added to either the clean data list or the bad data list.

The goal was to understand how data engineers clean and verify data before it’s stored or processed further. It uses basic Python logic like loops, conditionals, and functions to simulate real data quality checks.

---

## What I Did
- Created a list of fake data records with names, emails, and sales values.  
- Wrote a function (`check_record`) that checks each record for errors.  
- Separated good and bad records into two different lists.  
- Printed out the results showing which data passed and which failed.

---

## Example Output

- Clean Data: [{'name': 'John Doe', 'email': 'john@example.com', 'sales': 150}]
- Bad Data: [{'name': 'Alice', 'email': 'alice@', 'sales': -20}, {'name': '', 'email': 'bob@example.com', 'sales': 90}]
