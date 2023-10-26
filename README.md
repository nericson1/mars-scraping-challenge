# mars-scraping-challenge

## Description
This repository is constructed in two primary parts. Part One is `part_1_mars_news.ipynb` and contains the results of using splinter and BeautifulSoup to scrape specific information off the website linked here: https://static.bc-edx.com/data/web/mars_news/index.html. 

Part Two is `part_2_mars_weather.ipynb` and contains the results of using splinter and BeautifulSoup to scrape information from a table off the website linked here: https://static.bc-edx.com/data/web/mars_facts/temperature.html. 

Using this scraped information, further analysis was done to determine temperature and pressure patterns throughout the year.

## References
### Scrape an HTML table using BeautifulSoup into Pandas
I used the link below to figure out the best way to take the information I had gathered from the HTML table using BeautifulSoup, and turn that into a Pandas DataFrame. I tried a couple of different methods that were unsuccessful. After doing research, I found this link and used the steps and pointers provided to successfully construct my DataFrame. This can be seen in cell 6 of the part_2_mars_weather.ipynb file.

Link: https://saturncloud.io/blog/how-to-scrape-an-html-table-with-beautiful-soup-into-pandas/
