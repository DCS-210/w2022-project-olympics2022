Olympics 2022
================
by Amy Townend, Sam Simmons, Dylan Williams

## Summary
The 2022 Winter Olympics which was hosted in Beijing included the participation of 91 countries and 2871 athletes. This was the 24th Winter Olympics and it faced the lowest viewer rate in Olympic history of 11.4 million viewers. The Olympics have always been a time for countries to come together among political and economic conflicts and celebrate their athletes. The time in which the Olympics were canceled was due to world wars in 1916, 1940, and 1944. When a country is chosen to host the Olympics, it is a great honor. Countries will spend millions in order to ensure their athletes are ready to perform at the best. Sports have always been a test of natural skill but as technology has grown, so has the economic advantage. Richer countries have the disposable income to spend on the best coaches, equipment and even location. For the Winter Olympics, this is especially important to note as winter sports require even more funding to train for. In the famous movie Cool Runnings, a group of Jamaican track runners band together to become the first Jamaican bobsled team at the Olympics. This movie has a light hearted comedy feel to it but it reflects a true economic and climate advantage issue that is present with the Winter Olympics. The climate in Jamaica is hot and windy. Over the course of the year, the temperature typically varies from 73°F to 89°F and is rarely below 71°F or above 91°F. In comparison to Russia who receives snowfall about 6 months out of the year and face temperatures below -40°F. As anyone can see, this climate in Russia gives the an automatic advantage over warmer climates such as Jamaica. For the Winter Olympics, we see that a climate variable greatly affects athletes ability to train therefore affecting medal count. 

For our project, we decided to investigate the effect of climate and economic status on medal count at the Winter 2022 Olympics. We got our data from Kaggle in which someone created a data set which was updated daily with the new medal count. In order to get climate data on the countries we chose, we were able to access another database on Kaggle which gave us the average temperatures. Finally, in order to judge how an economic status would affect a country’s ability to have good athlete participation, we downloaded a data set from the World Bank. In order to get a good feel on the number of athletes qualified vs total population, we also collected total populations from 2020 since that is the most present data we could get. In order to run our visualizations and regressions, we were able to merge these data sets in a summary data frame. This is a very preliminary study into correlations between these variables and an extensive analysis would needed to be done with much more data and variables to avoid omitted variable bias. 

We wanted to explore the relationship between a country's GDP and the number of gold medals a country had. In order to get a result, we ran a linear regression model and receieved a R^2 value of 0.09337504. This tells us that a little over 9% of the varianvce in the average GDP in a country explains the number of gold medals. This makes us think that the average GDP is not enough information to predict the number of gold medals a country might achieve. This was not a surprise to us since as we have done our research we have found there are so many variables that could affect medal count. We were hoping to see a bit of a higher R^2 value but that is how good research is done. When the R^2 value is low it means that our independent variable is not explaining much in the variation of your dependent variable. For us, our independent variable is the average GDP and the dependent variable is the number of gold medals. One way to better our prediction is to deal with omitted variable bias. There are many variables that could better our regression such as population vs number athletes, funding to sports, and climate. However, adding variables does not necessarily increase our R^2 value. We would need to use an adjusted R^2 value in order to see if adding any variables would help better our predictor. 

For another data visualization, we graphed population versus number of athletes per country. These variables are important to analyze because there are several takeaways from comparing population and number of athletes per country. The reason most of the data on the graph is close to the y-axis is because there is a large outlier on the right side that causes a distinctive distribution of athletes per country. China has quite a large population, deviating from the average population, at 1439323776 people. Another notable takeaway from the graph is that Norway has the greatest number of olympic medals, 37. 



## Presentation

Our presentation can be found [here](presentation/presentation.html).

## Data

* Sarkhel, Arjun Prasad 2022, "2022 Winter Olympics Beijing", Kaggle , viewed 19 February 2022, https://www.kaggle.com/datasets/arjunprasadsarkhel/2022-winter-olympics-beijing.
* World Bank. "GDP (constant 2015 US$)" World Development Indicators, The World Bank Group, 2015,https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.
* Worldometer. "Countries in the world by population (2022)", https://www.worldometers.info/world-population/population-by-country/
* Freedom House. "Global Freedom Scores" Freedom House, 2020, https://freedomhouse.org/countries/freedom-world/scores
* Chavan, Akshay 2020, "Average Temperature per country per year", Kaggle, viewed 22 February 2022, https://www.kaggle.com/code/akshaychavan/average-temperature-per-country-per-year/data
## References

* Background Image: https://olympics.com/ioc/olympic-rings
* Image 1: https://www.disneyplus.com/movies/cool-runnings/1zyvW8wIgqET
* Image 2: https://www.sportingnews.com/us/olympics/news/olympics-medal-count-2022-gold-silver-bronze/q7x3klukq471udtxhrsawd5w
