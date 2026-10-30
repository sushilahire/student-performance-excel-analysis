# Student Performance & Attendance Analysis (Excel)

Internship task for TekLoomy: turning a raw, messy student dataset into
clean data, formula-driven analysis and a dashboard.

## Project Overview
The dataset had 159 raw records with deliberate quality problems: duplicates,
inconsistent labels, mixed date and number formats, invalid emails, missing
values and impossible ages, marks and attendance counts. I cleaned it,
documented every change, and analysed performance and attendance.

## Workbook Structure
| Sheet | Purpose |
|---|---|
| RAW_DATA | Original data, unchanged |
| CLEANED_DATA | 150 unique students with formula columns and data validation |
| FORMULA_PRACTICE | About 70 formulas across 7 categories with live results |
| SUMMARY | Key metrics, course and batch comparisons, top and bottom lists |
| DASHBOARD | KPI cards and 6 charts |
| ASSUMPTIONS | Grading scale, pass mark and attendance threshold |
| CLEANING_LOG | 791 documented changes (audit trail) |
| EXCLUDED_RECORDS | 9 excluded rows with reasons |

## Data Cleaning Highlights
- Removed 6 exact duplicates; excluded 3 unusable rows (documented, not deleted)
- Standardised names, IDs, courses, batches, genders, cities and statuses
- Fixed 10 malformed emails and converted text dates and numbers
- Flagged impossible values (age 0, scores above maximum, attended > held)
- Rebuilt attendance %, total score and grade with formulas

## Excel Skills Demonstrated
SUM, AVERAGE, MEDIAN, STDEV, IF / IFS / nested IF, AND / OR, TRIM, PROPER,
SUBSTITUTE, LEFT / MID / FIND, DATEDIF, EDATE, NETWORKDAYS, VLOOKUP,
INDEX-MATCH, COUNTIFS, SUMIFS, AVERAGEIFS, MAXIFS / MINIFS, SUMPRODUCT,
IFERROR, IFNA, data validation, conditional formatting, charts.

## Key Findings
- Only 51% of students have complete assessments; 73 are pending
- Pass rate among assessed students: 75.3%; average score: 51.5%
- Average attendance is 49.2%, and 66 students are below the 75% threshold
- 27 internships marked "Completed" do not have a passing result
- Web Development scored highest (61.2%); Power BI lowest (40.6%)

## Tools
Microsoft Excel (formulas, data validation, conditional formatting, charts)

## Files
- `Student_Performance_Analysis.xlsx`: the full workbook
- `Report`: a short data-quality and insights report
