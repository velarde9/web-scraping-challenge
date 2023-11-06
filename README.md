# web-scraping-challenge

# Part 1: Web Scraping
In this assingment, text elements were extracted from the Mars news site (visited using automated browsing).
The part_1_mars_news.ipynb Jupyter notebook contains code that scrapes the Mars news titles and preview text.
Titles and preview texts were extracted and stored in a Python dictionary which was used to Analyze the Mars Weather Data.

# Part 2: Scrape and Analyze Data
The part_2_mars_weather.ipynb Jupyter notebook contains code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data. 
The text elements that were scraped were then assembeled into a Pandas DataFrame with the following headings: 
- id: the identification number of a single transmission from the Curiosity rover
- terrestrial_date: the date on Earth
- sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
- ls: the solar longitude
- month: the Martian month
- min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
- pressure: The atmospheric pressure at Curiosity's location

The data was then converted to the appropriate data types.
After the DataFrame was created, Pandas was used to analyze the Mars weather data and visuals were created to support the ana;lysis. 
