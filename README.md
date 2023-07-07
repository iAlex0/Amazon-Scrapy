# Basic-scrapy-project
This is project scrapes Amazon.com with a specific query (i.e. Ipads), and returns the following data for each product:
- name
- price
- stars
- rating count
- features
- images
- variant data

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

1. Clone this project: `git clone https://github.com/iAlex0/Amazon-Scrapy.git`
2. Create a Python Virtual Environment: `python3 -m venv venv`
3. Activate the Python Virtual Environment: `venv/Scripts/activate`
4. Change working directory to the project folder: `cd basic-scrapy-project`
5. Install the project requirements: `pip install -r requirements.txt`
6. Add your API key to the settings.py file (https://www.scrapeops.io): 
    - SCRAPEOPS_API_KEY = 'YOUR_API_KEY'


7. Listing the scrapy projects `scrapy list` 
8. Running the scrapy project: `scrapy crawl amazon_search_product -O results.json` 


----------------------------------------------------------------------------------------------------------------------------

#### To expedite the scraping process, signup for a paid plan at https://www.scrapeops.io and then update the settings.py file:

CONCURRENT_REQUESTS = 32


## License
MIT © iAlex0



