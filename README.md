# Luther
predicting the success of movies based off of tv shows 
For this project is scraped box office mojo and wikipedia to get information about movies and TV shows. I used wolfram alpha to adjust movie budgets and revenue for inflation.  After adjusting dollar values for inflation I built a linear model to predict revenue based off of budget and other features.  After applying the model to all films to see which films over or underperformed there projections.  Then I looked at all movies based off of TV shows to see if any if the popularity(determined buy the number of seasons or episodes that the show ran for) of the TV show could explain any of the difference between the the projected and actual success of the movie.  I turns out that information about the TV shows did not explain anything.  Although I did discover that just the fact that a movie was based off of a TV meant that it behaved differently than a regular movie.  The difference between the regular model and the model trained only on movies based on TV shows was statistically significant.  The budget of movies based on TV shows appears to have less of an effect on the revenue than it does for other movies. 