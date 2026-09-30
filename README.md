# Import Data using Transform Maps (Spreadsheet)

## Project Overview

This project demonstrates how structured employee data from an external Excel spreadsheet can be imported into ServiceNow using Import Sets and Transform Maps.

The workflow stages the spreadsheet data in an Import Set table, maps the source fields to a custom target table, transforms and validates the data, and uses Coalesce on Employee ID to help prevent duplicate records.

## Source Data

The Excel spreadsheet contains the following fields:

- Employee ID
- Name
- Email
- Department
- Location

## ServiceNow Target Table

**Table:** Employee Test  
**Table Name:** `u_employee_test`

### Target Fields

| Source Field | Target Field |
|---|---|
| Employee ID | Employee ID |
| Name | Employee Name |
| Email | Email |
| Department | Department |
| Location | Location |

**Coalesce Field:** Employee ID

## Project Workflow

1. Create the employee data spreadsheet.
2. Create the ServiceNow target table.
3. Load the spreadsheet using Import Sets.
4. Create the Import Set staging table.
5. Create and configure the Transform Map.
6. Map source fields to target fields.
7. Enable Coalesce using Employee ID.
8. Transform and validate the imported data.
9. Create reports and a dashboard.

## Repository Structure

### 1. Brainstorming & Ideation
Contains the problem statement, empathy map, and idea prioritization documents.

### 2. Requirement Analysis
Contains the customer journey map, data flow diagram, solution requirements, and technology stack.

### 3. Project Design Phase
Contains the problem-solution fit, proposed solution, and solution architecture.

### 4. Project Planning Phase
Contains the project planning documentation.

### 5. Project Development Phase
Contains the coding and solution documentation, code layout, readability and reusability documentation, and functional feature documentation.

### 6. Project Testing
Contains the testing documentation.

### 7. Project Documentation
Contains the project executable files documentation and sample project documentation.

### 8. Project Demonstration
Contains communication, demonstration planning, proposed feature demonstration, scalability and future planning, and team involvement documentation.

## Team

- **Surya Prakash T** - Team Lead
- **SUNDAR P**
- **Varun S**
- **Sreehari B**

## Demo

The project demonstration video is provided separately through the SkillWallet Demo Link.
