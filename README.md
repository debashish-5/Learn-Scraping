## Project Overview

**[Learn-Scraping](https://github.com/debashish-5/Learn-Scraping)** is a hands-on learning repository created by [debashish-5](https://github.com/debashish-5). The project is dedicated to mastering web scraping methodologies using Python, walking through the process of programmatically connecting to websites, extracting raw web structures, and saving the unstructured data into formatted database logs.

---

## Key Features

* **HTTP Request Handling:** Demonstrates how to programmatically send web requests, configure request structures, and download raw webpage scripts.
* **HTML Parsing Engine:** Utilizes parsing tools to traverse HTML DOM trees, targeting and extracting specific elements, text contents, and localized tables.
* **Data Staging:** Structures the raw parsed results into tabular formatting and pipelines them into persistent data layers.

---

## Repository Structure

The project organizes its web scraping progression through localized Jupyter notebooks and target output sheets:

| File Name | Description & Purpose |
| --- | --- |
| **`01_Requests.ipynb`** | Covers foundational web calls, connection parameters, and extracting raw network page payloads. |
| **`02_Beautifulsoup.ipynb`** | Implements structural HTML DOM parsing, node identification, and data extraction strategies. |
| **`Page1.csv`** | The structured spreadsheet output containing data scraped from an individual page source. |
| **`Allpage.csv`** | An aggregated tracking sheet capturing compiled records scraped across multiple web pages. |

---

## Tech Stack

* **Languages:** Python
* **Core Libraries:** Requests, BeautifulSoup4
* **Environment:** Jupyter Notebook (100% of the codebase)
