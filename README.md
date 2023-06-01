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

  <img width="453" alt="1Untitled" src="https://github.com/odwct/Data-Collection/assets/126130532/d2065b8b-176f-4cf2-ae20-54145d91fdc0">
   
   As shown in the following graph, in the Martian year, the third month is the coldest, with an average temperature of -83.307 °C, and the hottest month is month 8, with      an average temperature of -69.172 °C.
    
    <img width="443" alt="2Untitled" src="https://github.com/odwct/Data-Collection/assets/126130532/0c994841-6b00-4115-a6ce-5077e7dcfed2">
    
4. Which month, on average, has the lowest atmospheric pressure? The highest?

    In the following graph, Mars's lowest atmospheric pressure is in the sixth month, while its highest atmospheric pressure is in the ninth month.
    
    <img width="441" alt="3Untitled" src="https://github.com/odwct/Data-Collection/assets/126130532/06ed5528-a039-4726-ba25-50ac2df58c1b">
    
5. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
    The first peak was approximately at 125 terrestrial days
    The second peak was approximately at 800 terrestrial days
    The third peak was approximately at 1475 terrestrial days
    
    Therefore,

    800−125=675
 
    1475−800=675
 
    According to the previous calculation, there are approximately 675 days that elapse on Earth between the hottest month of a Martian year and the next hottest month.
    Information confirmed through NASA confirms that each year on Mars takes 687 days on Earth.

    <img width="440" alt="4Untitled" src="https://github.com/odwct/Data-Collection/assets/126130532/44c49354-d5fc-42ae-adcb-2e7543dbfef0">

Reference
NASA, JPL and Caltech (no date) Mars in A minute: How long is a year on Mars? – NASA mars exploration, NASA. Available at: https://mars.nasa.gov/resources/21392/mars-in-a-minute-how-long-is-a-year-on-mars/#:~:text=The%20Earth%20zips%20around%20the,year%20means%20longer%20seasons%20too. (Accessed: 31 May 2023). 
