# Cyber Security Breaches Analysis

This project provides an SQL-based analysis of cybersecurity breaches. The scripts are designed to create a database and perform various analyses on the dataset, which includes metrics like the number of breaches, the affected individuals, and the business associates involved.

## Table of Contents

- [Project Description](#project-description)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [License](#License)
- [Acknowledgements](#acknowledgements)

# Project Description
The goal of this project is to analyze data on cybersecurity breaches to understand their scope and impact. The SQL scripts provided will help you:

- Set up a database for storing breach data.
- Analyze the total number of breaches, the number of unique states affected, the total number of individuals affected, and the distinct business associates involved.

# Prerequisites
To run the SQL scripts in this project, you'll need:

- MySQL Server: Installed locally or accessible remotely.
- SQL Client: Tools like MySQL Workbench, DBeaver, or the MySQL command-line client to execute SQL scripts.

# Usage
The SQL script contains multiple queries for analyzing cybersecurity breaches:

1. Database Setup:

- Creates a database named cyber_security_breaches if it does not exist.
- Selects the cyber_security_breaches database for use.

2. Data Analysis:

- Selects all data from the cyber security breaches table.
- Describes the table structure to understand its schema.
- Counts the total number of breach records.
- Counts the unique number of states affected by breaches.
- Calculates the total number of individuals affected across all breaches.
- Counts the number of unique business associates involved in the breaches.

3. Custom Analysis:

- Feel free to modify the SQL queries to tailor the analysis to your specific needs.

4. License

Distributed under the MIT License. See LICENSE for more information.

5. Acknowledgements

Data Source: https://www.kaggle.com/datasets/alukosayoenoch/cyber-security-breaches-data
