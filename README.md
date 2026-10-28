# Saudi Commercial Registrations Analysis
### Power BI | Data Cleaning | Dimensional Modeling | DAX

An end-to-end analytics project exploring active commercial registrations in Saudi Arabia through Q1 2026. The project focuses on data preparation, dimensional modeling, and developing an interactive Power BI dashboard to analyze registration trends, capital, entity types, and regional distribution.

## Dashboard Preview

![Saudi Commercial Registrations Dashboard](https://github.com/AbdullahHKA/Saudi-Commercial-Registrations-Analysis/blob/main/DashboardPh.png)

## Data Model

![Power BI Data Model](images/data-model.png)

## Project Workflow

### 1. Data Preparation and Cleaning
The source data was reviewed and cleaned to improve consistency and analytical usability. Key steps included:
- Removing extra spaces and standardizing text values.
- Reviewing missing values and handling them as appropriate for the analysis.
- Identifying and addressing negative capital values.
- Reviewing data quality and consistency before modeling.

### 2. Dimensional Data Modeling

A dimensional model was created to support analysis across time, geography, and registration classifications.

- **Fact_records:** Registration-level data used for analysis.
- **Dim_date:** Date attributes for time-based analysis.
- **Dim_Region:** Region and city attributes, including latitude and longitude for geographic analysis.
- **Dim_Entity_type:** Entity type, legal structure, and commercial activity classifications.
- **Measurss:** DAX measures used by the report.

### 3. DAX Measures

DAX measures were developed to calculate key indicators and support time-based analysis, including:
- Total registrations.
- Total capital.
- Cumulative registrations.
- Previous-year registration comparison.
- Year-over-year growth.
- Regional analysis measures.

### 4. Dashboard and Analysis

The Power BI report provides:
- KPI cards for registrations, regions, and total capital.
- Registration trends over time.
- Registration distribution by entity type.
- Geographic distribution across Saudi Arabia using region coordinates.
- Regional growth comparisons.
- Capital trends over recent years.

## Tools and Technologies
- Microsoft Power BI
- Power Query
- DAX
- Dimensional data modeling
- Data quality and cleaning techniques
- Geographic visualization using latitude and longitude

## Data Privacy

The repository contains dashboard and model screenshots only. The original source data is not included. Do not publish source records or the PBIX file unless you have permission and have confirmed that they contain no confidential or sensitive information.

## Author

**Abdullah Alasiri**
