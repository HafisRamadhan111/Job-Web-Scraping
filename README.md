# Job-Web-Scraping
How the Program WorksThis web scraping program runs through the following stages:

Preparation Stage (Import & Request): Uses the requests library to call the target URL and retrieve raw data from the website.
Reading HTML Data: Converts the received HTML data into a structured format that is easy to extract using BeautifulSoup from the bs4 module.
Preparing the CSV File: Uses the with open() statement to create a new CSV file that serves as a storage place for the execution results.
Processing Job Vacancy Data: Runs a loop to find and extract information from each job vacancy card one by one, then writes it directly into the CSV file.
