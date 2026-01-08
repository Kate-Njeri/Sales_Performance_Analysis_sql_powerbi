# Sales Performance Analysis
# Objective
The goal of this project is to design a sales analytics solution that helps answer key business questions:
- How are sales performing overall?
- Which regions are growing profitably, and which need attention?
- Which products should be pushed, fixed, or reconsidered?
- Are discounts supporting growth or eroding profit margins?
- How is sales performance distributed across sales representatives?
The output is a focused dashboard designed to support pricing, expansion, and sales strategy decisions.

# Data Source
_What data is needed to achieve our objective?_
Sales Data for the Time Period of January 2025 – December 2025

_Where is the data coming from?_
The dataset used in this project is from ChatGPT and represents a structured sales transactions dataset, capturing activity in 2025.

# Project Stages
This project followed a structured analytics workflow:
1. Design
2. Development
3. Testing
4. Analysis

# Design
## Dashboard Mock-Up
Before building the dashboard, I designed a conceptual layout to ensure:
- Clear metric hierarchy
- Alignment with the Sales Manager's decision needs

The dashboard is structured into:
- Executive overview (KPIs)
- Regional performance
- Monthly trend
- Product performance
- Discount impact
- Sales representative performance

_What should it look like?_

## Tools
- Excel – data preparation, validation
- SQL – data transformation, aggregation, and business logic
- Power BI – data modeling, DAX measures, and visualization

# Development
## a. Pseudocode
_What's the general approach in creating this solution from start to finish?_
1. Get the data
2. Explore the data in Excel
3. Load the data into SQL Server
4. Clean the data with SQL
5. Test the data with SQL
6. Visualize the data in Power BI
7. Generate the findings based on the insights
8. Write the documentation & commentary
9. Publish the data to GitHub Pages

## b. Data Exploration
This is the stage where I scan what’s in the data: errors, inconsistencies, bugs, weird and corrupted characters etc.

_What are the initial observations with this dataset? What’s caught my attention so far?_
* There are at least 3 columns that contain the data we will not need for this analysis, without needing to contact the client for any more data.
* The first column contains the Transaction ID with appropriate IDs, with the first two letters being the initial letter of the country where the transaction occured.
* We have more data than we need, so some of these columns would need to be removed.

## c. Data Cleaning
_What is the expected clean data to look like? (What should it contain? What constraints should we apply to it?)_
The aim is to refine our dataset to ensure it is structured and ready for analysis.

The cleaned data should meet the following criteria and constraints:
1. Only relevant columns should be retained.
2. All data types should be appropriate for the contents of each column.
3. No column should contain full values, including complete data for all records.

Below is a table outlining the constraints on our cleaned dataset:

## d. Transform the Data
## e. Create the SQL View
# Testing
## Data Quality Tests
# Visualization
## a. Results
## b. DAX Measures
# Analysis
## a. Findings
## b. Validation
## c. Discovery
# Recommendations
## a. Potential ROI
## b. Potential Courses of Action
# Conclusion
