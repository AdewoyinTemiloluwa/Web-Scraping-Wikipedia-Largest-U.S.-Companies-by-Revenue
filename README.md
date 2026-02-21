# Web-Scraping-Wikipedia-Largest-U.S.-Companies-by-Revenue
The script automates the collection of key metrics for the top 100 U.S. companies, transforming raw HTML into a structured dataset ready for business intelligence or exploratory data analysis (EDA).

---

### 📌 Project Overview
This project extracts data from the Wikipedia page “List of largest companies in the United States by revenue” and saves it as a structured CSV file for analysis. The scraped table contains information on the largest publicly traded companies in the U.S., including:
* Rank
* Company Name
* Industry
* Revenue (USD millions)
* Revenue Growth
* Employees
* Headquarters"
---

### 🛠 Tech Stack
* **Language:** Python
* **Web Scraping:** `BeautifulSoup`, `requests`
* **Data Manipulation:** `pandas`
* **File Handling:** `StringIO` (for efficient memory-to-DataFrame conversion)
---

⚙️ The ETL Process
* **Request**: Dispatched an HTTP request to the Wikipedia source using the requests library.
* **Parse**: Utilized BeautifulSoup to navigate the HTML DOM and isolate the wikitable element.
* **Extract**: Targeted specific table rows and data cells to capture revenue, growth, and employee counts.
* **Transform**: Cleaned string artifacts and loaded the raw data into a Pandas DataFrame.
* **Load**: Exported the final structured dataset to Companies.csv.
---

### 🎯 Key Skills Demonstrated

* **HTML DOM Navigation:** Targetting specific elements, classes, and tags.
* **Automated Data Collection:** Replacing manual "copy-pasting" with scalable code.
* **Data Integrity:** Handling inconsistent table formatting during the scraping process.
* **Documentation:** Presenting technical workflows for stakeholders.

---
📂 Data Access & Repository
You can access the live dataset and the source code through the links below:
* [Original Data Source](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)
* [Structured Dataset]()
* [Source Code]()

---

**Would you like me to add a "Future Improvements" section to show how you'd scale this (e.g., adding data visualization or database integration)?**
