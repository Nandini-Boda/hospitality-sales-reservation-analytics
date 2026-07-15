# 🏗 Solution Architecture

## Overview

This project automates hotel sales and reservation reporting from the Property Management System (PMS) into an executive dashboard.

The architecture minimizes manual reporting by automating data extraction, validation, storage, and visualization.

---

## Data Flow

Hotel PMS

↓

Google Apps Script Automation

↓

Google Sheets Database

↓

Data Validation & Transformation

↓

Looker Studio Dashboard

↓

Management Reporting

---

## Components

| Component | Purpose |
|-----------|----------|
| Hotel PMS | Source system for reservation and sales transactions |
| Google Apps Script | Automated data extraction and scheduled refresh |
| Google Sheets | Intermediate data storage |
| Data Validation | Cleaning and preparing business data |
| Looker Studio | Interactive executive dashboard |
| Management Team | Decision making using business KPIs |

---

## Automation Schedule

- Automatic refresh using Google Apps Script
- Scheduled data synchronization
- Dashboard updated after every refresh

---

## Benefits

- Eliminates manual reporting
- Centralized reporting
- Near real-time business visibility
- Faster executive decision making
