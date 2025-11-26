# Data Processing & Analysis Capstone Project using Python
## ✅ Project Overview

This project focuses on performing end-to-end data manipulation, transformation, cleansing, integration and analysis using Python—primarily through Pandas and NumPy. The dataset consists of three separate tables representing Employees, Projects and related attributes.
The project simulates a real-world data engineering and data analytics workflow where raw structured data is imported, cleaned, enriched, combined and analyzed to derive actionable insights.

The project covers essential data science concepts such as handling missing values, feature engineering, conditional updates, joins, grouping, filtering and exporting results. Performance evaluation emphasizes accuracy, problem-solving approach, logical thinking and familiarity with Python data workflows.

## ✅ Key Features & Tasks Covered

→ Data Ingestion & Export

    • Load three raw tables into Pandas DataFrames

    • Save cleaned data as CSV files for reuse

→ Data Cleaning & Preprocessing

    • Handle missing values using running average computed via a for loop

    • Split text fields into structured attributes (e.g., first and last name)

    • Replace, delete and update categorical values

→ Data Integration

    • Merge all three DataFrames into a single consolidated dataset named Final

→ Feature Engineering

    • Create a new bonus column based on project completion status

    • Add titles ("Mr." / "Mrs.") based on gender

    • Promote/demote designation levels based on business rules

→ Business Rule Automation

    • Demote employees with failed projects

    • Remove employees exceeding designation level threshold

    • Promote employees older than 29 using conditional logic

→ Exploratory Data Analysis

    • Aggregate total project cost per employee

    • Filter employees based on city text pattern ("o")
  
→ Data Output & Reporting

    • Export cleaned and aggregated outputs into DataFrames

## ✅ Technologies, Tools & Terminology Used

→ Core Programming Language

    • Python 3.x

→ Primary Libraries

    • Pandas → DataFrames, joins, filtering, aggregation, exporting CSV

    • NumPy → numerical operations, array manipulation

→ Important Functions & Concepts Used

    • pd.read_csv(), df.to_csv()

    • isnull(), fillna(), loops for imputation

    • str.split(), drop(), concat(), merge()

    • Conditional operations → np.where(), if, apply()

    • Grouping & aggregation → groupby(), sum()

    • Filtering using string matching → str.contains()

    • Data cleaning, normalization, feature extraction

    • Data Engineering Concepts

→ Handling missing values

    • Data normalization and column restructuring

    • Dataset joins and mapping

    • Conditional transformations

    • Data quality checks

→ File Formats

    • CSV (Comma-Separated Values)

## ✅ Conclusion

This project successfully demonstrates the ability to handle real-world structured datasets using Python and Pandas. It showcases strong foundational skills in data wrangling, preprocessing, integration and applied business logic.

## By completing the tasks, the project proves proficiency in:

→ Cleaning incomplete datasets

→ Structuring raw data into meaningful attributes

→ Automating rule-based updates

→ Feature creation for analytical insights

→ Performing aggregations and filtering to answer business questions

Overall, the project reflects readiness for entry-level to intermediate roles in data analysis, data science and data engineering—where working with unstructured data, extracting insights and delivering clean, usable datasets is essential.
