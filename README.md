# Mission-to-Mars

Robin loves astronomy and wanted help creating a Mars web scraping project. Web scraping with Python can pull data from multiple websites, store it in a database (MongoDB), then present the collected data on a webpage using Flask. Following this outline, I helped Robin scrap images and data from three different web pages and displayed the information with Flask and an HTML template.

![webscraping](https://raw.githubusercontent.com/jmsuarez1997/Mission-to-Mars/main/Resources/webscraping_map.png)

## Overview 
Python, Splinter, and BeautifulSoup were used to scrape Mars web pages and MongoDB to store the scraped data. Listed below is a procedure outline of the steps taken to create our webpage: 

1. Parse the HTML from webpages 
2. Select the data that you want and the tags associated with it 
3. Create tables and save data to MongoDB
4. Connect the MongoDB to the Flask web framework
5. Create an HTML template to show off your data.

## Webpages Scraped for Data
1. https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html#

2. https://mars.nasa.gov/all-about-mars/facts/

3. https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars


## Tools
1. Flask 
2. MondoDB
3. Beautiful Soup
4. Splinter
5. lxml (Used to parse HTML in Python)
6. html5lib (Used to parse HTML in Python)
7. Chrome Developer Tools
8. Visual Studio Code
