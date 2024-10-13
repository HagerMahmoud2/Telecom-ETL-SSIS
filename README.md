# Telecom-ETL-SSIS
## Project Overview

Telecom-ETL-SSIS is a robust Extract, Transform, Load (ETL) solution designed to handle telecom data efficiently using SQL Server Integration Services (SSIS). The project processes large volumes of telecom-related data, including critical fields such as IMSI, IMEI, and EVENT_TS. It ensures data quality through validation, error handling, and thorough logging, making the data ready for analytics and reporting.
Features

    Data Extraction: Reads data from flat files (CSV) and other telecom data sources.
    Data Transformation & Validation: Applies strict mapping rules and validation logic to fields like IMSI, IMEI, and timestamps.
    Data Integrity: Invalid records are rejected and stored in a separate error table for review.
    Comprehensive Error Handling: Logs all errors encountered during extraction and transformation phases.
    Data Auditing: Metrics like the number of processed, stored, and rejected records are tracked for full traceability.
    Automated Workflow: Processed files are moved to designated folders to maintain an organized system.

Technologies Used

    SQL Server Integration Services (SSIS): The primary tool for developing the ETL pipeline.
    SQL Server: The database for storing and processing telecom data.
    SSMS: Used for managing and querying data.

Data Transformation & Validation:

    Processed critical fields such as IMSI, IMEI, and EVENT_TS based on strict mapping rules.
    Ensured data integrity by rejecting records that didn't meet criteria, storing them in a separate table for review.

Data Quality Assurance:

    Stored essential metrics like the number of processed, stored, and rejected records.
    Linked processed records back to their original CSV files, ensuring full traceability.

Efficient Data Storage:

    The ETL process is designed to store validated data in a structured database model that aligns with business requirements.

Automated File Management:

    Processed CSV files are automatically moved to designated folders, ensuring a clean and organized file system.
