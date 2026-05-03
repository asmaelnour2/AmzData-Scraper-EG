Amazon Egypt Product Scraper 🛒

OverviewThis project is a high-performance Web Scraper built with Python and Selenium designed to extract product data from Amazon Egypt. It is engineered to handle dynamic web elements and navigate through multiple search result pages to gather comprehensive datasets.  

Key FeaturesDynamic Content Extraction: 
Utilizes Selenium to interact with JavaScript-heavy pages that traditional scrapers might miss.  
Automated Pagination: Automatically navigates through "Next" pages to maximize data collection.  
Comprehensive Data Points: Scrapes essential product details including Name, Price, Star Ratings, and Image URLs.  
Robust Error Handling: Implements try-except blocks to ensure the script continues running even if specific product data is missing.  

Tech Stack 
Language: Python
Automation: Selenium WebDriver  
Data Handling: Pandas (for structured output) 

How It Works
The script initializes a Chrome WebDriver instance.  
It navigates to a predefined Amazon Egypt search result URL.  
The scraper loops through the product containers, identifying and extracting data using CSS selectors or XPaths. 
Data is stored in a structured format (like a CSV file), making it ready for downstream Business Intelligence or Data Engineering pipelines. 

Future Improvements
Integrating a Power BI dashboard to visualize the scraped pricing trends.
Implementing headless mode for faster background execution.
Adding proxy rotation to avoid IP blocking.
