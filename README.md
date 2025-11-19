Programming Language
JavaScript (Node.js environment)

Technologies & Frameworks
Cypress - End-to-end testing framework

xlsx (SheetJS) - Excel file manipulation library

Excel/XLSX - Data storage and results tracking

Project Overview
A JavaScript-based automation system that performs Google searches and captures search suggestions using Cypress.

Key Components
1. search.cy.js (Test File)
Reads search keywords from an Excel sheet

Automates Google searches for each keyword

Captures search suggestions and identifies:

Longest suggestion

Shortest suggestion

Updates results back to the Excel sheet

2. searchAndUpdate.js (Data Handler)
Automatically selects Excel sheet based on current day of week

Manages reading/writing operations to Excel file

Provides data to tests and updates results in real-time

Workflow
Input: Keywords from daily Excel sheet

Process: Automated Google searches + suggestion analysis

Output: Longest/shortest suggestions written back to Excel

Tech Stack
Cypress for browser automation

xlsx library for Excel operations

JavaScript for core logic

Workflow
JavaScript → Cypress → Google Search → Excel Data Processing → Results Storage
