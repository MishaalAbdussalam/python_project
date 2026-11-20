# Python Data Analytics Projects

This project focuses on cleaning and preparing a customer call list dataset using Python and Pandas.

The dataset contains customer information, including names, phone numbers, addresses, payment status, and contact preferences.
The primary objective was to identify and address data quality issues, remove unnecessary information, standardise inconsistent values, and prepare the dataset for use in a customer contact list.

## Projects

### 1. Data Cleaning – Customer Call List

**Dataset:** Customer Call List.xlsx

**Objective:**
- Identify and remove duplicate records.
- Remove unnecessary columns
- Clean and standardise customer names.
- Standardise phone number formatting.
- Separate address information into individual columns.
- Standardise customer payment and contact preference values.
- Remove customers who should not be contacted.
- Handle missing values and validate the final dataset.

**Final Data Validation:**

Performed final checks to assess the quality and structure of the cleaned dataset using:
- df.info() - To get a high level overview of the dataframe.
- df.isnull().sum() - To find out if there are any null values in any columns. Empty strings are not counted as null values in this operation.
- df.duplicated().sum() - To find out if there are any duplicated records.
- df.shape - For the number of rows and columns.

**Key Learnings:**

Through this project, I gained practical experience in:

- Importing Excel datasets into Python.
- Using Pandas for data manipulation.
- Identifying and handling duplicate records.
- Cleaning inconsistent text values.
- Standardising phone number formats.
- Splitting and transforming columns.
- Handling missing values.
- Filtering records based on business requirements.
- Validating the quality of a cleaned dataset.

**Tools:** Python, Pandas, Jupyter Notebook.

### 2. Exploratory Data Analysis – World Population

**Dataset:** world_population.csv

**Objective:** Explore and analyse world population data to identify trends, patterns and insights.

**Key Areas Covered:**
- Data exploration and inspection.
- Analysing population distributions.
- Exploring population trends.
- Comparing population across countries and regions.
- Data analysis and visualisation.

**Tools:** Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook.

## Technologies Used

- Python - Programming and data analysis
- Pandas - Data manipulation and cleaning
- Matplotlib - Data Visualisation
- Seaborn - Statistical Visualisation
- Jupyter Notebook - Analysis

## Acknowledgements

These projects were completed for educational purposes as part of my Data Analytics learning journey.
Special thanks to Alex The Analyst for the tutorials and learning resources.
