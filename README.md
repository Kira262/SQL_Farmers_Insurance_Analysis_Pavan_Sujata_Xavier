# Farmers Insurance Data Analysis

## Overview

This project aims to analyze the Farmers Insurance dataset to understand the impact of various insurance schemes provided to farmers across different states and districts in India. The analysis includes retrieving specific information, aggregating data, filtering records based on certain criteria, and performing advanced SQL functions to derive meaningful insights.

## Problem Statement

The primary objective of this analysis is to evaluate and understand the impact of various insurance schemes provided to farmers across different states and districts in India. The analysis aims to identify trends, summarize key metrics, and derive insights from the Farmers Insurance dataset.

## Analysis Approach

The analysis is divided into several sections, each focusing on specific queries and data operations to extract meaningful information from the dataset:

1. **Data Preparation:**
   - Enable `local_infile` option for loading local files.
   - Create a schema and table to store the Farmers Insurance data.
   - Load data from a CSV file into the table.

2. **Data Retrieval (SELECT Queries):**
   - Retrieve unique state names and their short names.
   - Calculate the total number of farmers covered and the sum insured for each state.
   - Filter records based on specific criteria (e.g., year, population).

3. **Data Aggregation (GROUP BY):**
   - Calculate average insured land area per year.
   - Summarize total farmers covered and premium amounts by state and district.

4. **Data Filtering (WHERE Clauses):**
   - Retrieve records based on specific conditions (e.g., population thresholds, year).
   - Filter data to focus on relevant subsets for analysis.

5. **Data Sorting (ORDER BY):**
   - Identify top and bottom entities based on specific metrics (e.g., population, premium amounts).
   - Sort data to highlight key insights.

6. **String Functions:**
   - Manipulate and extract parts of text data (e.g., state short names, district names).

7. **Joins and Subqueries:**
   - Perform joins to combine data from multiple tables.
   - Use subqueries to filter data based on aggregated results.

8. **Advanced SQL Functions (Window Functions):**
   - Utilize window functions to compute cumulative sums and rankings.

9. **Data Integrity and Constraints:**
   - Define primary keys and foreign keys to maintain data integrity.
   - Create additional tables for states and districts with appropriate constraints.

10. **Update and Delete Operations:**
    - Modify specific records based on conditions.
    - Remove records that meet certain criteria.

## Results and Insights

- **State-wise Analysis:**
  - Identified states with the highest and lowest numbers of farmers covered.
  - Analyzed premium amounts and insured land areas across different states and years.

- **District-wise Analysis:**
  - Highlighted districts with significant population and insurance coverage.
  - Evaluated premium amounts and coverage ratios for different districts.

- **Trend Analysis:**
  - Observed trends in insurance coverage and premium amounts over the years.
  - Identified key factors affecting insurance uptake among farmers.

## Conclusion

The analysis provides a comprehensive overview of the Farmers Insurance dataset, highlighting key insights and trends. It serves as a valuable resource for policymakers and stakeholders to understand the impact of insurance schemes and make informed decisions to improve farmer welfare.

## Group Name

Query Crew

## How to Use

1. **Setup Database:**
   - Enable `local_infile` option in MySQL.
   - Create the schema and table using the provided SQL script.
   - Load the data from the CSV file into the table.

2. **Execute Queries:**
   - Use the SQL queries provided in `analysis_results.sql` to perform the analysis.
   - Modify and adapt the queries as needed to explore different aspects of the dataset.
