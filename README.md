# Video-Game-Sales-Analysis
Data Analysis identifying what factors make a video game succeed, for a hypothetical online game store (Ice) to plan future marketing around successful releases

## Background 

This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

## Objective
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.

(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 2026.)

The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

*Skills Used: Data PreProcessing, Exploratory Data Analysis, Statistical Data Analysis*

### Data Description
* Name
* Platform
* Year_of_Release
* Genre
* NA_sales (North American sales in USD million)
* EU_sales (sales in Europe in USD million)
* JP_sales (sales in Japan in USD million)
* Other_sales (sales in other countries in USD million)
* Critic_Score (maximum of 100)
* User_Score (maximum of 10)
* Rating (ESRB)
* Data for 2016 may be incomplete.

### Conclusion
The objective of this project was to identify patterns that determine whether a game succeeds or not.

Below are insights discovered:

* The top 5 most popular platforms in the world since 1985 are the PS2, Xbox 360, PS3, Wii, and DS.
* New platforms generally take about 10 years to appear and old ones to fade
* From 2013-2016, PS4 games outsold it's competitors by a large margine and sold the most units, followed by the PS3, and then the Xbox One.
* There is close to no correlation between user score and total sales for PS4 (most popular platfrom from 2013-2016) games.
* There is a moderate correlation between critic score and total score for PS4 games. As critic score improve, total sales moderately improve.
* From 2013-2016, The shooter and sports genres were the most popular across all platforms.

There are several factors that work in tandem that determine whether a game succeeds or not, with the most important being genre, the platform(s) that the game is sold on, and critic scores.

## Libraries Used
- Pandas
- Matplotlib.pyplot
- seaborn
- scipy.stats
- numpy
