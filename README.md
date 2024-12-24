# Data-Fetching

This repository showcases two distinct methods for fetching and processing data: **API Integration** and **Web Scraping**. Each method is documented and implemented in separate folders with its own set of use cases and examples.

---

## **Repository Structure**

- **Data Fetching Through API**  
  This folder contains scripts and examples demonstrating how to fetch data programmatically using APIs.  
  Example: Cryptocurrency market data retrieved from the CoinGecko API.

- **Data Fetching Through Web Scraping**  
  This folder includes scripts and examples for extracting data directly from websites using web scraping techniques.  
  Example: Job listings scraped from websites like RemoteOK and Indeed.

---

## **Features**

### 1. **Data Fetching Through API**
- **Technology Used**: Python (`requests`, `pandas`)  
- **Example API**: CoinGecko API for cryptocurrency market data.  
- **Outputs**:  
  - Fetches real-time cryptocurrency data, including:
    - Market cap
    - Current price
    - 24-hour price changes
  - Saves the data into a structured CSV file.  

### 2. **Data Fetching Through Web Scraping**
- **Technology Used**: Python (`requests`, `BeautifulSoup`, `pandas`)  
- **Example Websites**: RemoteOK, Indeed.  
- **Outputs**:  
  - Extracts job-related information, including:
    - Job titles
    - Company names
    - Locations
    - Salaries (if available)
    - Application links
  - Saves the scraped data into a structured CSV file.

---

## **How to Use**

1. Clone the repository:  
   ```bash
   git clone https://github.com/muhammadnouman911/Data-Fetching.git
   cd Data-Fetching
