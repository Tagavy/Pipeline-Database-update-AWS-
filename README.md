# Pipeline-Database-update-AWS
This project is dedicated to keeping databases regularly updated by means of automated pipelines. The project focuses on the 3 main parts: 
* data collection, 
* pushing data to the cloud, and 
* automating data updating. 

It requires basic knowledge of Python Pandas and MySQL.
It is advisable to use the presented materials together with [the article](https://medium.com/@tagavy8/always-fresh-always-juicy-8bee31928db0)
 to ensure an efficient implementation of the project. The article demonstrates how to use automated pipelines, Pandas, MySQL, and AWS to keep databases regularly updated. By following the outlined steps, you can ensure that your databases are always up to date, and ready to serve your business needs.

## Tools used 
### Libraries and Packages:
Pandas: Used for modifying and converting data into a database.
Requests: Used to send a request to and get a response from a web server.
BeautifulSoup: A library for parsing the data received from a web server.
Regex: Used for data cleaning.
NumPy: Used for data cleaning.

### Tools and Technologies:
Python: The programming language used throughout the process.
MySQL: The database management system used for storing data.
AWS (Amazon Web Services): The cloud platform used to host the database and automate data updating.
Lambda: AWS service for running code in response to events, used for automating data collection and updating.

## Stages:
**Web Scraping**: Used to extract data from websites.\
**API Requests**: Used to collect data from APIs.  
**Data Cleaning**: Process of preparing the data for pushing into the database.  
**Pushing the Data**: Process of inserting the collected and cleaned data into the database.  
**Creating an Instance on AWS**: Creating a virtual server to host the database.  
**Connecting to MySQL**: Establishing a connection between MySQL and the AWS instance.\
**Automating Data Updating**: Using Lambda functions and triggers to schedule and automate the data updating process.

Happy automating!
