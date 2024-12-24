# Data Fetching Through Web Scraping

This folder demonstrates how to extract data from websites using web scraping techniques. It includes scripts for fetching data from different web pages and saving it into structured CSV files. The examples focus on job listings, book details, and other real-world data scraping use cases.

---

## **Project Overview**

The project showcases the use of web scraping to collect data from websites where APIs are unavailable or insufficient. By using Python libraries such as `BeautifulSoup` and `requests`, the scripts extract information from HTML content, parse it, and save it into structured formats like CSV.

### **Features**
- Scrapes data from multiple sources:
  1. **Books to Scrape**: Extracts book titles, prices, ratings, and availability.
  2. **Indeed**: Fetches job listings with titles, companies, locations, and salaries.
  3. **RemoteOK**: Scrapes remote job listings, including titles, companies, locations, and application links.

- Outputs structured datasets for further analysis.

---

## **Files in This Folder**

1. **Data Fetching Through Web Scraping.ipynb**  
   - Jupyter Notebook showcasing the web scraping process for various websites.

2. **books_dataset.csv**  
   - Dataset containing book details scraped from "Books to Scrape".

3. **indeed_dataset.csv**  
   - Dataset of job listings scraped from Indeed.

4. **remote_jobs.csv**  
   - Dataset of remote job listings scraped from RemoteOK.

---

## **How to Use**

### **Prerequisites**
- Install the required Python libraries:
  ```bash
  pip install requests beautifulsoup4 pandas
