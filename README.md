# Retail Sales ETL Pipeline

## Project Overview
A beginner-friendly ETL (Extract, Transform, Load) pipeline built in 
Python that demonstrates core Data Engineering concepts. Raw messy 
sales data is extracted, cleaned and transformed using Pandas, then 
loaded into a SQLite database for storage and querying.

## Tools Used
- Python
- Pandas
- SQLite3
- Google Colab

## ETL Process
**Extract** — Raw sales data with real world issues including missing 
values, duplicates, and inconsistent formatting

**Transform** — Data cleaned using Pandas:
- Fixed inconsistent capitalization on customer names and products
- Removed duplicate records
- Filled missing values with column averages
- Dropped rows with missing critical fields
- Added calculated total sales column

**Load** — Cleaned data loaded into a SQLite database and verified 
by reading back out

## Pipeline Results
- Raw records extracted: 10
- Clean records loaded: 8
- Records removed: 2
- Total sales value loaded: $7,250.96

## Key Concepts Demonstrated
- ETL pipeline architecture
- Data cleaning and transformation
- Database loading with SQLite
- Data validation and verification
