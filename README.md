# ETL Pipeline with Delta Lake in Databricks

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Data Quality Checks](#data-quality-checks)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview
This project implements a robust ETL (Extract, Transform, Load) pipeline in Databricks using Delta Lake. It efficiently manages data across three layers: Bronze, Silver, and Gold, ensuring data quality, integrity, and insightful analysis through various transformations and aggregations.

## Technologies Used
- Databricks
- Delta Lake
- Apache Spark
- Python
- Power BI

## Installation
1. Sign up for [Databricks Community Edition](https://community.cloud.databricks.com/).
2. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/riakundra_12/ETL-Pipeline-with-Delta-Lake-in-Databricks.git
   
## Usage
1. **Upload your dataset (CSV) to Databricks:** Load your dataset into the Databricks environment for processing.
2. **Run the provided notebooks:** Execute the code in the notebooks that correspond to each step of the ETL process (Bronze, Silver, Gold layers).
3. **Review the outputs:** After running the notebooks, check the results and any visualizations generated during the process for insights.

## Project Structure
- `/bronze`: Stores the raw data as Delta tables.
- `/silver`: Contains the cleaned and transformed data in Delta format.
- `/gold`: Holds the aggregated and processed data, ready for reporting and analysis.
- 
## Features
- **Bronze Layer:** Ingest raw data and save it as a Delta table using Delta Lake’s schema enforcement and ACID properties.
- **Silver Layer:** Perform data cleaning, transformations, and create enriched datasets.
- **Gold Layer:** Perform aggregations, filtering, and prepare data for reporting and analytics.
- **Data Quality Checks:** Identify and log data quality issues, such as null values, duplicates, and schema mismatches.
- **Visualization:** Create visualizations from Gold layer data for reporting using Power BI or other tools.

## Data Quality Checks
The project includes the following data quality checks:
- **Null Value Check:** Ensures no critical fields contain null values.
- **Duplicate Check:** Identifies duplicate records and removes them from the dataset.
- **Schema Validation:** Verifies data type consistency and enforces schema evolution rules.
- **Audit Logging:** Logs any data quality issues to a separate Delta table for later auditing.

## Visualization
This project generates key insights from the Gold layer data, which can be visualized using Power BI or similar tools:
- **Total Profit per Product Category**
- **Number of Orders by State**
- **Top Customers by Total Spend**
- **Average Profit per Order by City**
- **Revenue per Product**
  
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments


Project developed as part of Veersa Technologies training program,
Special thanks to Mr. Manoj Pal for mentorship and guidance
- **[Databricks](https://databricks.com/)** for providing the platform for data processing and analysis.
- **[Delta Lake](https://delta.io/)** for enabling reliable data storage and schema enforcement.
- **[Apache Spark](https://spark.apache.org/)** for its powerful distributed computing capabilities.
- **[Power BI](https://powerbi.microsoft.com/)** for data visualization and reporting.
- Special thanks to the open-source community for the tools and resources that helped shape this project.


   

