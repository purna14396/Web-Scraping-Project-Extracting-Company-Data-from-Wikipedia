# Web Scraping Project: Extracting Company Data from Wikipedia

## 📌 Overview
This project demonstrates how to scrape data from a Wikipedia page listing the largest companies in the United States by revenue. Using **Python**, **BeautifulSoup**, and **pandas**, the script extracts the table, processes it into a structured **DataFrame**, and exports it as a CSV file for further analysis using pandas.

## 🔗 Source Website
[Wikipedia: Largest Companies in the United States by Revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

## 📜 Features
- 🔍 **Web Scraping with BeautifulSoup**: Extracts tabular data from a Wikipedia page.
- 📚 **Data Parsing and Cleaning**: Removes unnecessary whitespace and organizes data.
- 📊 **Pandas Integration**: Stores the extracted data in a structured DataFrame.
- 💾 **CSV Export**: Saves the cleaned data for further use.
- 🛠 **Error Handling & Debugging**: Addresses common scraping issues.

## 🚀 How It Works
1. **Send a request** to fetch the HTML content of the Wikipedia page.
2. **Parse the page** using BeautifulSoup and identify the relevant table.
3. **Extract table headers** and row data.
4. **Store the data** into a pandas DataFrame.
5. **Export the data** into a CSV file for further analysis.

## 🏗 Dependencies
Ensure you have the following installed before running the script:
- `beautifulsoup4`
- `requests`
- `pandas`

## 📌 Key Takeaways
- Understanding **web structure** is crucial for effective scraping.
- Using **pandas DataFrames** simplifies data handling.
- Debugging is an integral part of the scraping process.
- Always check website terms of service before scraping.



