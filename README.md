# TechWay Analysis Project

## Overview

This project analyzes helpdesk tickets to enhance understanding of common issues, response times, and overall efficiency. It includes three datasets:

1. **TechWay-AnalysedWork.xlsx** - Analysis of helpdesk tickets.
2. **helpdesk_tickets.xlsx** - Raw helpdesk ticket data.
3. **Ticket and Date Created List.xlsx** - Ticket IDs with creation dates.

## Files Description

### 1. TechWay-AnalysedWork.xlsx
This file contains the results of our detailed analysis after proper data cleaning:
- Summary statistics of ticket counts and resolution times.
- Trends analysis for ticket creation and resolution.
- Performance metrics: response times and SLA compliance.
- Common issues reported by users.

### 2. helpdesk_tickets.xlsx (located in the `raw_data` folder)
- Ticket ID: Unique identifier.
- Issue Description: Detailed report.
- Resolution: Solution provided.
- Created Date: Timestamp of creation.
- Resolved Date: Timestamp of resolution.
- Priority: Priority level (e.g., High, Medium, Low).

### 3. Ticket and Date Created List.xlsx (located in the `raw_data` folder)
- Ticket ID: Unique identifier.
- Created Date: Date of creation.

## Data Cleaning
We conducted thorough data cleaning to ensure the accuracy and reliability of the analysis:
- Removed duplicates and irrelevant entries.
- Handled missing values appropriately.
- Standardized date formats and ticket categories.
- Verified data consistency across datasets.

The results of this clean and processed data are found in **TechWay-AnalysedWork.xlsx**.

---

## Summary Worksheet
In addition to the above, this repository contains an Excel file, `TechWay-Formulas.xlsx`, with a worksheet named "Summary." The file calculates and displays key ticket metrics based on the cleansed data provided.

1. Total Tickets per Team
2. Total Tickets per Priority
3. Total Tickets per Type
4. Total Open Tickets
5. Total Resolved Tickets
6. Total Closed Tickets
7. Total Open/Answered Tickets
8. Total Tickets from “Email”
9. Total Tickets from “Web”
10. Total Tickets from “Phone”
