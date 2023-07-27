# Retrieve missing files from the downloaded dataset using the SEC API.

We uploaded 8k and 10k forms for sp400, sp500, sp600, but due to connection disruptions, some files are missing. It is necessary to find which files are missing and download them.
Conditions:
1. The official documentation for the SEC API: https://www.sec.gov/edgar/sec-api-documentation
2. You have two lists of companies from Wikipedia:
   - List of S&P 400 companies: https://en.wikipedia.org/wiki/List_of_S%26P_400_companies
   - List of S&P 500 companies: https://en.wikipedia.org/wiki/List_of_S%26P_500_companies
   - List of S&P 600 companies: https://en.wikipedia.org/wiki/List_of_S%26P_600_companies
3. The dataset can be found here: https://drive.google.com/drive/folders/1yf20ZGRHuXVX9p8CMcJu5_xbnhGtNmtY?usp=sharing
4. You can start from a baseline https://github.com/jp-strategy/edgar_missing/blob/main/edgar_base.ipynb
5. You can use alternative libraries for querying the database.

Steps to complete the task:

Study the official documentation of the SEC API to understand how to make queries and retrieve data from the database.
Compare the downloaded dataset with the company lists from Wikipedia and fillings from EDGAR database to identify missing file.
Use your preferred programming language and library to make API requests and download the missing files.

The task evaluates your ability to work with APIs, use documentation effectively, and handle real-world scenarios in programming. Good luck with the task! 
