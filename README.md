# Faculty Roster & D2L Upload Tool

**Streamline the process of building semester instructor reports and D2L template rosters.**

## Upload a course schedule and faculty email list to generate:

* A structured Excel report of instructors by course, campus, and support status
* Ready-to-upload D2L roster `.txt` files for each subject and role combination

---

## Features

* Cleans and standardizes instructor data from raw CSV exports
* Flags co-requisite **support courses** 
* Skips placeholders like "Staff" to focus on assigned instructors
* Groups instructor rosters by **campus** and **course**
* Outputs:

  * `List_of_Instructors_by_Course_<timestamp>.xlsx`
  * Individual `.txt` rosters: `MATH 1111 instructor roster.txt`, etc.

---

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

* Department and course curriculum chairs preparing D2L course shells each semester  
* Administrative staff managing campus-specific teaching assignments  
* Academic operations teams conducting instructional support and assessment analysis

---

## Sample Outputs

*(Include screenshots or file links here)*
