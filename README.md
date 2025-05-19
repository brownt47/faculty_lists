# Faculty Roster & D2L Upload Tool

**Streamline the process of building semester instructor reports and D2L template rosters.**
Upload a course schedule and faculty email list to generate:

* A structured Excel report of instructors by course, campus, and support status
* Ready-to-upload D2L roster `.txt` files for each subject and role combination

---

## Features

* Cleans and standardizes instructor data from raw CSV exports
* Flags co-requisite **support courses** and **PLC (Perimeter Learning Community)** sections
* Skips placeholders like "Staff" to focus on assigned instructors
* Groups instructor rosters by **campus** and **course**
* Outputs:

  * `Faculty_List_Spring_2025_<timestamp>.xlsx`
  * Individual `.txt` rosters: `MATH 1111 instructor roster.txt`, etc.

---

## How to Use

### Run on Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](LINK-TO-YOUR-NOTEBOOK)

1. Upload your **semester schedule CSV**
2. Upload your **faculty email list CSV**
3. The notebook will:

   * Merge, clean, and analyze the data
   * Generate Excel and D2L-ready text files


---

## File Structure

```text
Faculty_List_Report.ipynb     # Main notebook
sample_data/
  sample_schedule.csv
  faculty_emails.csv
outputs/
  List_of_Instructors_by_Course_YYYYMMDD.xlsx
  MATH 1111 instructor roster.txt
requirements.txt
```

---

## Example Use Cases

* Department chairs preparing D2L shells for upcoming semesters
* Admin staff tracking faculty overloads and campus assignments
* Academic operations filtering by support/PLC criteria

---

## Sample Outputs

*(Include screenshots or file links here)*
