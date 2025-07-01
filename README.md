# Data-Engineering-and-Analytics

Requirements:
Objective: In this assignment, you will explore the process of ETL: data extraction, preprocessing,
transformation, and loading into a MySQL database server. You will also execute queries on the
integrated dataset to extract meaningful insights.
Task 1: Data Scraping
1. Choose a Website:
 Select a website that contains structured data relevant to your area of interest. Some
suggestions include:
o Wikipedia: for information on historical events, geographical data, biographies, etc.
o IMDb: for movie or television show data including ratings, cast, plot summaries, etc.
o Kaggle datasets: for a wide range of datasets on various topics including finance, healthcare,
sports, etc.
o Government data portals: for datasets related to demographics, economics, public health, etc.
2. Define Data to Scrape:
 Specify the specific information you want to scrape from the chosen website. This could
include:
o Table data: such as lists of items, statistics, or rankings.
o Text data: such as article content, descriptions, or reviews.
3. Scrape the Data:
 Utilize Python libraries such as BeautifulSoup, requests to scrape the desired data from the
website.
The Hashemite University
Prince Al-Hussein bin Abdullah II Faculty for IT
Department of Information Technology
Data Engineering and Analytics ( 2010042211)
Assignment 1
Data Extraction and Integration Challenge
Due Date: 2-5-2024 11:59 PM
Max score: 15 points
 Implement web scraping techniques to navigate through the website's HTML structure and
extract the relevant information.
Task 2: Data Preprocessing and Transformation
1. Clean the Scraped Data (at least 2 tasks):
 Handle missing values, remove duplicates, and correct inconsistencies in the
scraped data.
2. Transform the Data (at least 3 tasks)::
 Normalize, standardize, or encode categorical variables as necessary.
 Convert the data into a format suitable for integration with the MySQL
database.
3. Integration
 Integrate the datasets into a unified dataset, addressing any potential data
quality issues that may arise during the integration process.
Task 3: Loading Data and Executing Queries in MySQL Database Server
A. Setup a Local MySQL Database:
 Install and set up a MySQL database server on your localhost using the provided
resources. Please refer to these websites https://ladvien.com/data-analytics-mysqllocalhost-setup/ and https://dev.mysql.com/doc/sakila/en/sakila-installation.html for
downloading and installing it.
B. Connect to the MySQL Database:
 Utilize the create_engine method in Python to establish a connection to the MySQL
database installed on your localhost.
C. Create a Database using Python Code:
 Write Python code to create a new database within the MySQL server using the
established connection.
D. Load the Integrated Dataset into the Database:
 Implement Python code to load the previously integrated dataset (from Task C) into
the newly created MySQL database. Ensure that the data is appropriately mapped to
the database schema.
E. Execute at Least 3 Queries of Your Choice:
 Write SQL queries to extract insights from the integrated dataset. For example:
 Retrieve the top 10 records from a specific table.
 Calculate summary statistics such as average, minimum, maximum, etc.
 Perform joins between multiple tables to combine relevant information

