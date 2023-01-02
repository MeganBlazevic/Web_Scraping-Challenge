# Web_Scraping-Challenge

For the Challenge 12, we were asked to complete a web-scraping and data analysis for the Mission to Mars.  Using HTML elements we have been asked to extract information and browsing with Spliter and parsing the data with BeautifulSoup.  The outcome of this challenge should enforce our past learnings; collecting data, organizing and properly storing the data, analysing, and then communicating our findings.

Programs Utilized
- Jupyter Notebook
- Beautiful Soup
- Splinter
- Python
- Pandas


## Part 1
### Web Scraping of Mars News
Using Jupyter notebook, I browsed the Mars NASA News site.  After inspecting the page, scraping elements were identficied.  BeautifulSoup was utilized to extract website elements. Data was stored in a Python dictionary. An optional task was to store the scraped data in a JSON or MangoDB database. 

After inspecting the Mars News website, the daily titiles and their preview statements were scraped from the website. A CSV was created with the mars_news data for viewing data scraped from the site. Data elements were also saved into a json file. 

## 2
### Analysis of Mars Weather
Using BeautifulSoup we scraped some data from the website and stored it into a Pandas DataFrame. Data analysis was then done on the weather. The DataFrame was exported into a CSV file. 

Data was pulled from an amazon aws regarding some Mars weather data.  This was a table that was stored in the html.  Upon inspection, data was scrapped; and then multiple queries were run to answer some questions. Upon answer the questions, the dataframe that was used was saved as a mars_data_table csv file. 
- How many months exisit on Mars?
    -  12 months
- How many Martian days worth of data exisit in the dataset?
    - 1867 days
- What are the coldest and warmests months on Mars?
    - Coldest months are months 3 and 4
    - Warmest is month 8
- Which months have the lowest and highest atmospheric pressures on Mars?
    - Lowest pressure is month 6
    - Warmest pressure is month 9
- About how many terrestrial days exisit in a Martian year?
    - 686 days


