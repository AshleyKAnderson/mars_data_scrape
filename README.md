# Mars Data Scrape

What You're Creating
This new assignment consists of two technical products. You will submit the following deliverables:

1. Deliverable 1: Scrape titles and preview text from Mars news articles.

2. Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


# Instructions
## Part 1: Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook, use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape. Create a Beautiful Soup object and use it to extract text elements from the website. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:

{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
Store all the dictionaries in a Python list.

Print the list in your notebook.


## Part 2: Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook, use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

**id**: the identification number of a single transmission from the Curiosity rover<br/>
**terrestrial_date**: the date on Earth<br/>
**sol**: the number of elapsed sols (Martian days) since Curiosity landed on Mars
**ls**: the solar longitude
**month**: the Martian month<br/>
**min_temp**: the minimum temperature, in Celsius, of a single Martian day (sol)<br/>
**pressure**: The atmospheric pressure at Curiosity's location<br/>


## Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Which months have the lowest and the highest atmospheric pressure on Mars? 
About how many terrestrial (Earth) days exist in a Martian year? 


