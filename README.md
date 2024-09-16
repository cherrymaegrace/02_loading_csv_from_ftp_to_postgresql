# Loading CSV files from an FTP Server to PostgreSQL using SSIS

This project is an output of the __[Episode 04](https://www.youtube.com/watch?v=m2DD-RvT-nA&t=1392s)__ of Josh Dev's Building Your First End-to-End Data Portfolio series.

## Output Overview
This output showcases the creation of an SQL Server Integration Services (SSIS) package that downloads CSV files from an FTP server and loads it into a PostgreSQL database.

## Learning Outcomes:
- Set-up PostgreSQL database
- Get familiar with SSIS interface 
- Create tasks to
  1. Download CSV files from an FTP server
  2. Load data into PostgreSQL database tables
  3. Join multiple tables into a single dataset

## Datasets
The following datasets from __[OFAC Consolidated List](https://sanctionslist.ofac.treas.gov/Home/ConsolidatedList)__ were used:
- CONS_PRIM.CSV
- CONS_ADD.CSV
- CONS_ALT.CSV
