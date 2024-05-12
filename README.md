# web-scraping-challenge

Module 11 Challenge

This new assignment is a web scraping cahllenge that requires 2 deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Deliverable 1:

Involved scraping data from a Mars news website using automated browsing with Splinter to visit the Mars news site, and extracting the html code with Beautiful Soup. The titles and preview text of the news articles were scraped, extracted and stored into a list of dictionaries.

This was sone in a jupyter notbeook named "part_1_mars_news" and stored in this repository as "part_1_mars_news.ipynb".


Deliverable 2: 

Involved scraping and analyzing Mars Weather Data.
The Mars Weather data website was opened using Splinter and the HTML table was extracted using Beautiful soup and  saved into a Pandas DataFrame named "df". The columns were appropriately named and the data types appropriately changed to allow easy analysis.

The data was analyzed usind pandas to answer and visualize the following questions: 

1.How many months exist on Mars?
2.How many Martian days' worth of data are there?
3.Which month, on average, has the lowest and highest temperature ?
4.Which month, on average, has the lowest  and highest atmospheric pressure?
5.How many terrestrial days exist in a Martian year?

The dataframe "df" was then saved into a csv file into the "output" folder within this repository's main branch as mars_weather.csv.
