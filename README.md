# Health Records Analysis in Excel

## Project Overview

This project demonstrates an end-to-end data analysis workflow using Microsoft Excel.

The dataset contained over 5,000 healthcare patient records with inconsistencies, missing values, duplicate records, formatting issues, and unstructured data.

The objective was to transform the raw dataset into a clean, analysis-ready dataset and generate meaningful insights through Excel formulas, PivotTables, and PivotCharts.

---

## Business Problem

Healthcare organizations rely on accurate patient records to make informed decisions about treatment costs, resource allocation, and patient care.

The raw dataset contained several data quality issues that could affect reporting and decision-making, including:

* Duplicate patient records
* Missing diagnosis information
* Missing doctor assignments
* Inconsistent date formats
* Inconsistent text entries
* Unstructured age categorization

The goal was to clean the data, standardize records, and create analytical reports that provide actionable insights.

---

## Dataset Information

The dataset contains patient visit information including:

* Patient ID
* Visit Date
* Age
* Gender
* Diagnosis
* Treatment Type
* Assigned Doctor
* Treatment Cost

Total Records Analyzed: 5,000

---

## Tools Used

* Microsoft Excel
* PivotTables
* PivotCharts
* Conditional Formatting
* Lookup Functions
* Statistical Functions
* Date Functions

---

## Data Cleaning Process

The following cleaning steps were performed:

### Duplicate Removal

* Removed duplicate records using PatientID as the unique identifier.

### Missing Value Treatment

* Replaced blank Diagnosis values with:

  * Unknown
* Replaced blank Doctor values with:

  * Unassigned

### Data Standardization

* Standardized Gender values:

  * Male
  * Female
  * Other

* Removed unnecessary spaces from:

  * Doctor
  * Treatment
  * Diagnosis

### Date Formatting

* Converted VisitDate into a standardized date format:

  * dd-mmm-yyyy

### Column Cleanup

* Removed the existing AGE RANGE column and rebuilt it using formulas.

---

## Excel Functions Applied

### Logical Functions

Used IF statements to create:

* Age Group
* Age Range Categories

Examples:

* Under 18
* Adult
* Aged

---

### Statistical Functions

Calculated:

* Average Treatment Cost
* Maximum Treatment Cost
* Minimum Treatment Cost
* Count of Patients with Diabetes

Functions Used:

* AVERAGE()
* MAX()
* MIN()
* COUNTIF()

---

### Lookup Functions

Created a Treatment Cost Reference Table and applied:

* VLOOKUP()

to retrieve standard treatment costs.

---

### Math Functions

Calculated:

* Cost With Tax

Formula:

Cost × 1.10

Functions Used:

* ROUND()
* ROUNDUP()
* ROUNDDOWN()

---

### Date Functions

Extracted:

* Year
* Month

Functions Used:

* YEAR()
* MONTH()

---

## Analysis Performed

### Total Treatment Cost by Doctor

A PivotTable was created to identify doctors associated with the highest treatment costs.

### Patient Distribution by Gender

A PivotTable and Pie Chart were created to analyze gender distribution across patients.

### Average Cost by Diagnosis

Calculated average treatment costs for each diagnosis category.

### Age Group Distribution

Analyzed patient demographics using custom age classifications.

---

## Key Insights

### Doctor Cost Analysis

The highest treatment costs were associated with:

* Dr. Wong
* Dr. Lee
* Dr. Patel

while Unassigned records accounted for the lowest overall cost contribution.

### Gender Distribution

The dataset shows a relatively balanced distribution across:

* Male
* Female
* Other

patient groups.

### Diagnosis Cost Analysis

Certain diagnoses generated significantly higher average treatment costs, highlighting areas that may require greater healthcare resource allocation.

### Patient Demographics

Most patients fell within the Adult and Aged categories, indicating a higher concentration of healthcare utilization among mature age groups.

---

## Project Deliverables

* Raw Dataset
* Cleaned Dataset
* Formula-Based Analysis Sheet
* PivotTables
* PivotCharts
* Summary Insights

---

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Validation
* Excel Formulas
* Lookup Functions
* Statistical Analysis
* PivotTables
* PivotCharts
* Data Visualization
* Business Insight Generation

---

## Author

Funmibi Akinsete

Aspiring Data Analyst | Excel | SQL | Power BI | Python

Focused on transforming raw data into actionable business insights.

