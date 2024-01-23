# **web-scraping-challenge**

# **Part 1: Scrape Titles and Preview Text from Mars News**
In the Jupyter Notebook file part_1_mars_news.ipynb

Use automated browsing to visit the following site: Mars news articles

Create a Beautiful Soup object and use it to extract text elements from the website.

Extract the scraped titles and preview text of the news articles and store the results as follows:

Store each title-and-preview pair in a Python dictionary with the two keys title and preview.
Store all the dictionaries in a Python list.
Print the list.
Export the scraped data to a JSON file (to ease sharing the data with others).

# **Part 2: Scrape and Analyse Mars Weather Data**
In the Jupyter Notebook file part_2_mars_weather.ipynb

Use automated browsing to visit the following site: Mars weather data

Create a Beautiful Soup object and use it to scrape the data in the HTML table.

Assemble the scraped data into a Pandas DataFrame. The column headings, with explanations, are:

id : the identification number of a single transmission from the Curiosity rover
terrestrial_date : the date on Earth
sol : the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls : the solar longitude
month : the Martian month
min_temp : the minimum temperature, in Celsius, of a Martian day (sol)
pressure : the atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int or float data types.

Analyse the dataset using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and warmest months on Mars (at Curiosity's location)? To answer this question:
Find the average minimum daily temperature for each month.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure for each month.
Plot the results as a bar chart.
How many terrestrial (Earth) days, approximately, exist in a Martian year? To answer the question:
Consider how many days elapse on Earth in the same time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.
