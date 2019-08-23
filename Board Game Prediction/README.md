INTRO-:
BoardGameGeek is an online forum for board gaming hobbyists and a game database that holds reviews, images and videos for over 84,000 different tabletop games, including European-style board games, wargames, and card games. In addition to the game database, the site allows users to rate games on a 1–10 scale and publishes a ranked list of board games.

Board game site annually awards the best new board games of the year with the Golden Geek Award. Winners are selected based on a vote by registered users.
My Insights-:
1.There were quite a few games with 0 Rating.Either those games were not launched or perhaps no one gave a shot to those games.
  I removed all the games with 0 rating.
2.The histogram plots shows us that it is a Multimodal plot with quite a few peaks and it was slightly skewed to left.
3.The correlation heat map shows that there is no direct correlation between Avg_User_Rating and different features.This made it complex to give accurate predictions.
4.Linear Regression gave a mean_squared_score of about 2.07
5.RandomForestRegressor gave a  mean_squared_score of about 1.44
6.Considering that there is no direct correlation between Avg_User_Rating and different game features the above score seems to be good enough.
