# project_mod2

# project2_football_analysis
Author: Seungwon Lee

Introduction:

This Mod2 Project asked us to use Pandas, SQL, OOP, API and NoSQL to: 

1) analyse our data, 
2) perform EDA, 
3) Use an API key to request the Weather on games played in 2011. 
4) Export the Data into a NoSQL (MongoDB)

Methodology:

I used SQL to import the data(given) to Jupyter Notebook and performed EDA on the data 
with a mixture of SQL and Dataframe with Pandas to tackle the questions. 
I then used matplotlib to plot our results for the visualisation and 
I managed to provide two box graph for German and English Football team.
Next, I requested the weather from DarkSky based on the dates of games played in the 2011 season using an API key. 
Due to the limited number of requests allowances, I exported the results into an csv file.
Finally, I used MongoDB to export each questions dataset and also to export the plots.

Summary Findings:

We found the number of Wins/Losses/Draws of each team in the 2011 season in Germany(Only D1) and England (Premier League).
We also saw in our dataset that when we used an API request to get the weather data many of them were 
Null values and there were very few rainy days where games were played and 
thus showing the percentage of wins in rainy days to total wins of each team 
would be a negligant (%) so I chose rather to show then number of wins/losses and total games played by each team in rain.
finally i used pymongo to export our data

Conclusion

Fortunately, it seems that the initial dataset from Kaggle is simple and relatively well-structured. 
but when performing EDA i noticed the format was not very easy to perform EDA on, 
so we had to do a perform a mixture of SQL with Pandas to collect and extract the neccessary date.
also on top of that the limitation of 1000 request was something i had to keep into consideration 
since i wanted to get the weather on about 900 entries and so i would only have one chance, 
so when it worked i made sure to export it into a csv file so i can call upon it without worry.
the Dataset was interesting and i would like to redo this again and apply OOP more thoroughly 
and also attempt to answer more questions on the data set.

Conclusion / Limitation

limited amount of rain data leading too poor interpretability of win rate

Data of Rainy days are only based in Berlin's location which was used to read across to teams in the EPL too.

