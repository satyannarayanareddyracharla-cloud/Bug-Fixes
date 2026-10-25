# Google Search with Selenium

A small Python example that opens Google in Chrome, searches for `Python Selenium`, and prints the search page title. The browser interaction is implemented with a page object in `pages/google_search_page.py`.

## Requirements

- Python 3.10 or later
- Google Chrome
- Selenium

Install Selenium:

```powershell
python -m pip install selenium
```

Recent Selenium versions can manage the Chrome driver automatically through Selenium Manager.

## Run

From the project root:

```powershell
python confest.py
```

The script opens Chrome, performs the search, and prints the page title. If Google presents an automated-traffic challenge, the script reports that search results are unavailable.
