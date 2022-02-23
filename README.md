# Video-Game-Sales-Analysis
Data Analysis identifying what factors make a video game succeed, for a hypothetical online game store (Ice) to plan future marketing around successful releases

### Background 

This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

### Project Setup
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.

(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 2026.)

The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

Skills Used: Data PreProcessing, Exploratory Data Analysis, Statistical Data Analysis

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

In Japan (2013-2016):

* The Nintendo 3DS was by far the most popular platform in Japan from 2013-2016, followed by the PS3 and PS4, respectively.
* The action genre had the most game releases in Japan from 2013-2016, but the most popular genres by median total sales were sports and puzzle, followed by role-playing.
The most profitable game rating is T and and E.

In North America (2013-2016):

* The Xbox 360 was the most popular platform in North America from 2013-2016, closely followed by the PS3 and Xbox One, respectively.
* The Nintendo 3DS was the least popular among the top 5 platforms in North America.
* The action genre had the most game releases in North America from 2013-2016, but the most popular genres by total median sales were sports, followed by shooter.
* The most profitable game rating in North America from 2013-2016 was E10+ followed by M.

In Europe (2013-2016):

* The most popular platform sold in Europe from 2013-2016 was the PS3, followed by the PS4 and then the Xbox 360.
* The Nintendo 3DS was the least popular among the top 5 platforms in sold in Europe.
* The action genre had the most game releases in Europe from 2013-2016, but the most popular genres by median total sales was shooter, followed by racing and fighting.
* The most profitable game rating in Europe was M, closely followed by E10+.


In conclusion, there are several factors that work in tandem that determine whether a game succeeds or not, with the most important being genre, the platform(s) that the game is sold on, and critic scores.

