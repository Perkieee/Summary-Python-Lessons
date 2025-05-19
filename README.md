# Summary-Python-Lessons
This repository contains key python lessons that help when tackling variety of problems when dealing with Data

## 📄 `webscraping.ipynb` — Web Scraping Practice Notebook

This Notebook demonstrates various levels of web scraping techniques using Python. It is organized as a learning and exploration resource, covering:

1. **Basic Table Scraping with BeautifulSoup**

   * Extracting structured table data from static HTML pages.
   * Parsing `<table>`, `<tr>`, and `<td>` elements.
   * Creating a clean pandas `DataFrame`.

2. **Scraping Paginated Data**

   * Handling traditional pagination (with “Next” buttons or numbered links).
   * Looping through multiple pages using `requests` and BeautifulSoup.
   * Dynamically constructing URLs and combining data from all pages.

3. **Scraping JavaScript-Rendered Content**

   * Using **Selenium** to interact with pages that load data via JavaScript/AJAX.
   * Clicking tabs or buttons to trigger dynamic data loading.
   * Waiting for page elements to appear before scraping (`WebDriverWait` and `ExpectedConditions`).
   * Extracting dynamically populated tables into structured `DataFrame`s.
  




### 🛠️ Tools & Libraries Used

* `requests`
* `BeautifulSoup` (bs4)
* `selenium`
* `pandas`
* `time` / `WebDriverWait` for loading synchronization
