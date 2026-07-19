# Web Scraping with Python & BeautifulSoup

Hey there! Welcome to this awesome Web Scraping project! 🔥 This document outlines a fantastic Python script that extracts job listings from the [Real Python Fake Jobs](https://realpython.github.io/fake-jobs/) website. 

##  What Does This Project Do?
This script powerfully and efficiently parses the website's HTML to scrape:
- **Job Titles** 
- **Company Names**
- **Locations** 
- **Application Links** 

And the best part? It automatically saves all this valuable data directly into a super clean CSV file named `Scrapping_Python.csv`! 

## Prerequisites
Before you dive in, make sure you have the following fantastic libraries installed:
- `beautifulsoup4`
- `requests`

You can easily install them using pip:
```bash
pip install beautifulsoup4 requests
```

## How to Run the Code
1. Ensure your Jupyter Notebook or Python environment is set up.
2. Run the cell that imports the libraries and fetches the website URL.
3. Run the parsing and extraction loop.
4. Run the final cell to save the data.
5. Boom! 💥 Check your directory for the freshly generated `Scrapping_Python.csv` file containing exactly 100 job listings!

## Output Format
The script successfully exports a file called `Scrapping_Python.csv` with the following clearly defined columns:
- `Job Title`
- `Company`
- `Location`
- `Apply Link`

Happy Scraping! Keep coding and stay awesome!
