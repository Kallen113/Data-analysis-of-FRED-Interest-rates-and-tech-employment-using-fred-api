# Data-analysis-of-FRED-Interest-rates-and-tech-employment-using-fred-api
Data analysis of FRED Interest rates and tech employment using FRED API to extract the data on interest rates. 


Many recent articles over the past year or so have identified two potential causes for the extensive layoffs within the tech industry in the United States: 1) more widespread usage and adoption of AI tools and software and additionally 2) increases in the Federal Reserve's target rate for interest rates, which started (for the first time in years) in March 2022. 

In this project, I will analyze the correlation between tech layoffs (in terms of aggregate U.S. totals) and Federal Reserve target rates. 

To do this, I seek to extract data on Federal Reserve interest rate targets. I will use the FRED API via Python to extract these data. 

For reference, here is the homepage for FRED's documentation on the FRED API: <https://fred.stlouisfed.org/docs/api/fred/overview.html>. In addition, a Python library actually exists that might work for thios project's purposes. The documentation for this Python library is available on pypi: <https://pypi.org/project/fredapi/#:~:text=First%20you%20need%20an%20API,to%20the%20evironment%20variable%20FRED_API_KEY>. 

To-dos:
1) Create Python script to make GET requests and grab data from the FRED API.
2) Extract 2021-2024 (up to most recently available) FRED data on Federal Reserve target interest rates.
3) Find data on tech layoffs for 2021 to 2024 (up to most recently available).
