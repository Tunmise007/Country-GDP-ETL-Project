# Country-GDP-ETL-Project

### Overview
This Python ETL (Extract, Transform, Load) project focuses on retrieving GDP (Gross Domestic Product) data for various countries from a specified webpage, transforming the data, and then saving it to both a CSV file and a SQLite database table. The project utilises web scraping, data manipulation, and database operations to achieve these objectives.

### Purpose
This ETL (Extract, Transform, Load) project is designed to automate the retrieval, transformation, and storage of Gross Domestic Product (GDP) data for various countries. The primary objectives include:

•	Data Extraction: Utilising web scraping techniques to extract relevant GDP information from a specified webpage.

•	Data Transformation: Converting GDP values from currency format to floating-point values and transforming GDP from USD (Millions) to USD (Billions) with precision rounding.

•	Data Storage: Saving the processed data into both a CSV file and an SQLite database table for easy accessibility and further analysis.

•	Logging: Implementing a logging mechanism to record progress and key messages throughout the execution of the ETL process.

### Features
1.	Web Scraping with BeautifulSoup: The project employs the BeautifulSoup library to scrape and extract GDP data from a designated webpage efficiently.
2.	Data Transformation: GDP values are meticulously transformed, ensuring consistency, and facilitating better analysis by converting to USD (Billions).
3.	Multiple Output Formats: The project supports flexibility by saving the final dataset in two formats - a CSV file for easy sharing and an SQLite database table for structured storage.
4.	Logging Progress: A comprehensive logging mechanism is in place to capture and record key messages at various stages of the ETL process. This aids in monitoring and troubleshooting.
5.	Query Execution: The ability to run SQL queries on the stored data provides users with the option to perform custom analyses tailored to their specific needs.
6.	Ease of Customisation: The code structure allows for easy customisation and adaptation to different data sources or requirements.
