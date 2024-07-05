# Mission to Mars

For the astrology enthusiasts, this project extracts the news from [MARS Planet Science](https://static.bc-edx.com/data/web/mars_news/index.htmlhttps:/) site. It then it goes to the [MARS Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html) to do analysis on the data provided in the site.

From the data science perspective, there are several methods to extract the data from these sites. On [part_2_mars_weather.ipynb](https://part_2_mars_weather.ipynb), 2 different methods are used to read the table:

* Pandas
* Selenium

Both methods are valid.

Afterwards, The following questions are answered:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
4. Which months have the lowest and the highest atmospheric pressure on Mars?
5. About how many terrestrial (Earth) days exist in a Martian year?


Final note:

* To see the extraction of the MARS Planet Science news, refer to [part_1_mars_news.ipynb](https://part_1_mars_news.ipynb)
* To see the extraction and data analysis of the MARS Temperature Data, refer to [part_2_mars_news.ipynb](https://part_2_mars_news.ipynb)
