# Data-Collection

## Part 1: Scrape Titles and Preview Text from Mars News
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).

The titles and preview text of the news articles were scraped and extracted.

The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

## Part 2: Scrape and Analyze Mars Weather Data
The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. 

The data was analyzed to answer the following questions: 

1. How many months exist on Mars? 
    The data on Mars indicate that there are 12 months in a year.
    
2. How many Martian days' worth of data are there?
    Based on the scraped data, we found data for 1867 days.
    
The data was analyzed to answer the following questions, and a data visualization was created to support each answer: 

3. Which month, on average, has the lowest temperature? The highest?
    
4. Which month, on average, has the lowest atmospheric pressure? The highest?
    
5. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
    


NASA, JPL and Caltech (no date) Mars in A minute: How long is a year on Mars? – NASA mars exploration, NASA. Available at: https://mars.nasa.gov/resources/21392/mars-in-a-minute-how-long-is-a-year-on-mars/#:~:text=The%20Earth%20zips%20around%20the,year%20means%20longer%20seasons%20too. (Accessed: 31 May 2023). 
