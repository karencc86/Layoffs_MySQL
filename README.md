# World Layoffs Data Cleaning Project (SQL)

## Project Overview
This project focuses on a comprehensive data cleaning process of a world layoffs dataset using MySQL. The goal was to transform a "dirty" raw dataset into a structured, reliable, and analysis-ready database.

## Technical Skills Applied
- **Data Protection:** Created staging tables to preserve the integrity of the original source.
- **Deduplication:** Utilized Common Table Expressions (CTEs) and Window Functions (`ROW_NUMBER()`) to identify and remove redundant records.
- **Data Standardization:** Applied string manipulation functions (`TRIM`, `LOWER`) and converted data types (converting text to `DATE` format).
- **Advanced Null Handling:** Analyzed and treated null values by populating missing information using self-joins and logical filtering.
- **Schema Optimization:** Modified table structures by adding/removing columns to enhance query efficiency.

## The Process
1. **Initial Diagnosis:** Explored the data to identify inconsistencies and total record counts.
2. **Normalization:** Standardized industry names and locations to ensure consistency.
3. **Null Hygiene:** Managed empty values and decided whether to impute or remove them based on data relevance.
4. **Validation:** Performed a final quality check to ensure the dataset was "healthy" and ready for Exploratory Data Analysis (EDA).

## Credits
Special thanks to **Alex The Analyst** for the guidance provided throughout this project.
