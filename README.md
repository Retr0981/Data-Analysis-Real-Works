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

## Welcome Back!

Hi there! 👋 I’m excited to share with you my latest project: TechWay-Formulas. This Excel workbook is crafted with care to help you dive into ticket data with meaningful insights and powerful calculations.

## What’s Inside?

### 1. Key Metrics

In the "Summary" worksheet, you’ll find a snapshot of important ticket metrics:
- **Total Tickets per Team**
- **Total Tickets per Priority**
- **Total Tickets per Type**
- **Total Open Tickets**
- **Total Resolved Tickets**
- **Total Closed Tickets**
- **Total Open/Answered Tickets**
- **Total Tickets from “Email”**
- **Total Tickets from “Web”**
- **Total Tickets from “Phone”**

These metrics are designed to give you a comprehensive overview at a glance.

### 2. New and Exciting: SLA Calculations

I’ve added a new dimension to our ticket analysis with SLA calculations! Here’s what’s new:
- **SLA Due Date**: I’ve introduced a column in the "Tickets List" to show the due date for each ticket based on its priority. 
  - **Emergency**: 4 hours
  - **High Priority**: 3 business days
  - **Normal**: 5 business days
  - **Low**: 10 business days
  - For “Request” types, it’ll simply say “No SLA for Request.”

- **Breached SLA?**: Another new column will indicate whether the SLA was breached. It will display “Yes” if the ticket is overdue and “No” if it’s still within the SLA period.

- **Ticket Viewer**: I’ve added a handy “Ticket Viewer” worksheet where you can enter any ticket number and get instant details on:
  - Subject
  - From
  - Date Created
  - Priority

This feature is designed to make tracking and managing tickets even easier.

## How to Use

1. **Clone** or **download** this repo to get started.
2. Open `TechWay-Formulas.xlsx` in Excel.
3. Check out the “Summary” sheet for a broad view of ticket metrics.
4. Explore the “Tickets List” for SLA details and breaches.
5. Use the “Ticket Viewer” to quickly look up ticket information by number.

## Feedback and Contributions

I’ve enjoyed putting this together and would love to hear your thoughts! Feel free to suggest improvements or share any issues you encounter. Your feedback is invaluable.


