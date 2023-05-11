# data_collection-challenge

This is a Web Scarping and Data Analysis challenge that uses Splinter and BeautifulSoup for scarping data from two sites, one related to Mars news articles, and the other Mars weather data from a table.

The challenge was divided into two parts:

**Part 1: Scrape Titles and Preview Text from Mars News**
    * Extract titles and previews text from news articles from a scraped website using Splinter and BeautifulSoup
        * Each article had its title and preview scrape and placed in a Python Dictionary presented as:
            {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
            'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}

    * Each Python Dictionary was stored into a Python list and printed

    * The Python data was exported to JSON file for ease of sharing 

**Part 2: Scrape and Analyse Mars Weather Data**
    * Scrape a data table from a website using Splinter and BeautifulSoup and placing the data into a Pandas DataFrame using the column headings:
        * id: the identification number of a single transmission from the Curiosity rover
        * terrestrial_date: the date on Earth
        * sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
        * ls: the solar longitude
        * month: the Martian month
        * min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
        * pressure: The atmospheric pressure at Curiosity's location

    * The data has been examined and was recast to appropriate data types where needed

    * A analyses of the data was undertaken to answer the following questions:
        * How many months exist on Mars? There are 12
        * How many Martian days’ worth of data exist in the scraped dataset? There is 1,867
        * What is the coldest and warmest months on Mars? Coldest was month 8 and the warmest was month 3
        * What months had the lowest and highest atmospheric pressure on Mars? Lowest was month 6 and the highest was month 9
        * How many Earth days exist in a Martian Year by visually estimating the daily minimum temperature line plot? Estimated at 675 days

    * The data file has been exported as CSV for review.
