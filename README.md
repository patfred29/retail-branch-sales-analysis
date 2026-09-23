# Multi-Branch Retail Sales Analysis

Independent project — 508-row retail transaction dataset across multiple branches, analyzed to answer real manager-style business questions.

## Workbook structure
- **Transactions** — raw, unedited data (mixed date formats, currency parsing issues, orphan branch/staff codes)
- **Cleaned_Transactions** — cleaned and standardized version with working lookup formulas
- **Branches** — branch code lookup table
- **Staff** — staff code lookup table
- **Pivot_Summary** — pivot table analysis

## What I did
- Built VLOOKUP and INDEX-MATCH formulas to pull Branch Name and Staff Name from the lookup sheets across 500+ rows
- Identified and fixed an off-by-one row-reference bug in a lookup formula that had misclassified over 500 rows into an incorrect fallback category
- Flagged a hardcoded fallback value that was silently masking multiple invalid branch codes
- Answered the manager's specific business question comparing sales by new vs. returning customers

## Tools
Excel (VLOOKUP, INDEX-MATCH, SUMIFS/COUNTIFS, Pivot Tables, structured references)

## Screenshots
![Pivot table view](Screenshot%202026-09-23%20193140.png)
![Analysis view](Screenshot%202026-09-23%20193158.png)
