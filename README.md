# Data Collection
Data analysis project using web-scraping UCB Data Analysis and Visualization Bootcamp Module 11 

### Deliverable 1: Scrape titles and preview text from Mars news articles.
The mars_news.ipynb Jupyter notebook uses automated browsing to open the Mars news website. It extracts titles and preview text from site and stores the scraped results in a dictionary.

### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
The mars_weather.ipynb Jupyter notebook scrape data from a static html file from https://static.bc-edx.com/data/web/mars_facts/temperature.html. It examines the data to analyze the following:
1. The number of sol (Martian days) per month on Mars
2. The coldest and the warmest months on Mars (at the location of Curiosity)
3. Months have the lowest and the highest atmospheric pressure on Mars
4. The number of terrestrial (Earth) days in a Martian year

Finally, the script exports the data into a csv file in the output folder - output/mars_weather.csv.