# Customer Issue Management Dashboard

## Overview

This project is an interactive Power BI dashboard designed to analyze and monitor customer issue cases.

The dashboard provides an overview of case volume, resolution performance, TAT compliance, product lines, regions, escalation levels, and case categories.

## Dashboard Features

- Total Cases
- Active Cases
- Closed Cases
- Average Resolution Days
- Overdue TAT Cases
- Within TAT Cases
- Monthly Customer Issue Trend
- Customer Issues by Product Line
- Customer Issues by Region
- Customer Issues by Category
- Customer Issues by Escalation Level
- Overdue Cases by Product Line
- Interactive Quarter and Month filters
- Case ID search
- Category filtering
- Reset Filters functionality
- Detailed case-level table

## TAT Monitoring

The dashboard classifies cases based on the number of days between the case Open Date and the relevant closing/current date.

- 60 days or less → Within TAT
- More than 60 days → Overdue TAT

## Tools Used

- Microsoft Power BI
- DAX
- Microsoft Excel

## Dataset

This project uses a synthetic dataset created specifically for demonstration and portfolio purposes.

No real customer information or confidential company data is included.

## Project Structure

```text
Customer-Issue-Management-Dashboard/
│
├── Customer_Issue_Management_Dashboard.pbix
├── Customer_Issue_Management_Dataset.xlsx
└── README.md