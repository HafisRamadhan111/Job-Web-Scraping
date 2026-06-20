# Job Listings Scraper

This project is a simple web scraping application using Python to extract job listing data. It was created to complete a challenge from roadmap.sh.

**Project URL:** https://roadmap.sh/projects/job-listings-scraper

## How the Program Works
1. **Preparation Phase:** Uses the `requests` library to fetch the raw data from the target website URL.
2. **Reading HTML Data:** Parses and structures the retrieved HTML data using `BeautifulSoup` from the `bs4` module.
3. **Preparing the CSV File:** Uses the `with open()` command to create a new CSV file to store the extracted results.
4. **Processing Data:** Iterates (*loops*) through each job posting to extract the required information one by one and writes it directly to the CSV file.
