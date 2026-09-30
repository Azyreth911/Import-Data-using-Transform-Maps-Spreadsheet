# Import Data using Transform Maps (Spreadsheet)

## Project Overview

This project demonstrates the workflow for importing structured employee data from an external spreadsheet into ServiceNow using Import Sets and Transform Maps.

The workflow includes spreadsheet preparation, staging the imported data, configuring field mappings, transforming the data into a custom ServiceNow table, validating the imported records, configuring Coalesce to help avoid duplicate records, and preparing reports and dashboards.

## Source Data

The spreadsheet contains the following fields:

- Employee ID
- Name
- Email
- Department
- Location

## ServiceNow Target Table

**Table:** Employee Test  
**Table Name:** `u_employee_test`

### Field Mapping

| Source Field | Target Field |
|---|---|
| Employee ID | Employee ID |
| Name | Employee Name |
| Email | Email |
| Department | Department |
| Location | Location |

**Coalesce Field:** Employee ID

## Project Workflow

1. Creation of the employee spreadsheet
2. Creation of the ServiceNow target table
3. Loading the spreadsheet using Import Sets
4. Creation of the Import Set staging table
5. Creation of the Transform Map
6. Mapping source fields to target fields
7. Configuring Coalesce using Employee ID
8. Transforming and validating the imported data
9. Creating reports and dashboards

## Repository Structure

### 1. Brainstorming & Ideation
Contains the problem statement, empathy map, and idea prioritization documentation.

### 2. Requirement Analysis
Contains the customer journey map, data flow diagram, solution requirements, and technology stack documentation.

### 3. Project Design Phase
Contains the problem-solution fit, proposed solution, and solution architecture documentation.

### 4. Project Planning Phase
Contains the project planning documentation.

### 5. Project Development Phase
Contains the coding and solution, code layout, readability and reusability, and functional feature documentation.

### 6. Project Testing
Contains the testing documentation.

### 7. Project Documentation
Contains the project executable files documentation and sample project documentation.

### 8. Project Demonstration
Contains the communication, demonstration planning, proposed feature demonstration, scalability and future planning, and team involvement documentation.

## Team

- **Surya Prakash T** - Team Lead
- **SUNDAR P**
- **Varun S**
- **Sreehari B**

## Demonstration

A project demonstration video is provided separately through the SkillWallet Demo Link.
