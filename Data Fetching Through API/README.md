# Data Fetching Through API

This folder demonstrates how to fetch and process cryptocurrency market data from the **CoinGecko API**. It includes scripts to retrieve real-time data such as prices, market capitalization, and trading volume, which are saved as structured CSV files for further analysis.

---

## **Project Overview**

The project focuses on fetching live cryptocurrency data programmatically using APIs. It provides insights into how to interact with APIs, parse JSON responses, and save the extracted data in a structured format.

### **Features**
- Retrieves data for **top cryptocurrencies** by market cap.
- Extracted data includes:
  - **Cryptocurrency Name**
  - **Symbol**
  - **Current Price**
  - **Market Cap**
  - **24-Hour Price Change**
  - **Trading Volume**
- Saves the data into **CSV files** for analysis and visualization.

---

## **Files in This Folder**

1. **Data fetching through API.ipynb**  
   - A Jupyter Notebook containing the Python script for fetching cryptocurrency data from the CoinGecko API.

2. **Final_cryptocurrency_dataset.csv**  
   - The processed dataset containing the fetched cryptocurrency data.

3. **cryptocurrency_dataset.csv**  
   - An additional dataset created during intermediate steps.

4. **README.md**  
   - This documentation file explaining the project and its contents.

---

## **How to Use**

### **Prerequisites**
- Python installed on your system.
- Required Python libraries:
  - `requests`
  - `pandas`

### **Steps**
1. Clone this repository and navigate to the folder:
   ```bash
   git clone https://github.com/muhammadnouman911/Data-Fetching.git
   cd Data-Fetching/Data\ Fetching\ Through\ API
