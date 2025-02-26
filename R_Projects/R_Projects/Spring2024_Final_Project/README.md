## Final Project - PSY 598 - BDS II

This was the Final Project I created for my PSY 598: Behavioral Data Science II course.

The purpose of this final project is to analyze a dataset of my choice, showcasing my proficiency in data analysis and machine learning techniques. For this project, I chose to examine gambling behavior, specifically, online gambling. Using this dataset, I conducted exploratory data analysis with visualizations, and built four distinct machine learning models (Boosted Tree, Random Forest, K-means, and KNN models), tuning parameters as necessary to optimize model performance. The project involves evaluating the predictive accuracy of these models and interpreting their insights within the relevant domain.

There are three major aims for this project:
1) Predict wins and loses of gambling.
2) Predict the “types of gamblers” players may be.
3) Explore the win or loss outcome two players playing the same game.

I explored a dataset containing behavior of gamblers using the online platform called Bustabit. This data was collected
from 10/31/2016 to 12/10/2016 and was found [here on Kaggle](https://www.kaggle.com/datasets/kingabzpro/gamblingbehavior-
bustabit/data).

The rules of the game are that you bet money in Bits and you must cash out before the game “busts.” Wins
are calculated using the amount of the bet multiplied by the amount cashed out. For example, you bet 10
and you cash out at 3.5, so your win would be 35 minus what you put in, so 25. Bonuses are also added and
must be multiplied by the bet. On Bustabit, the house also has a slight advantage, where for every 1 out of
100 games, all players bust.
