# NBA 2020
 Predicting the NBA games scores
I was really unhappy, when due to the C* crisis, the NBA league for 2020 got cancelled, and my favourite player Luka Doncic from Dallas is also out.

So I decided to make a short simulation, using various AI tools, and try to predict, how the league would end.

The files in this directory:

Scrape the data of all played NBA games in 2020

Make a predicition of the Win/Loose for all the pairs

Just for fun - I am trying to "predict" the number of points scored by each team playing head-to-head

You can see, that winning, and scoring is NOT perfectly correlated. Some of it depends even on the learning method used in the prediction. Simple, LASSO and Ridge Regressions generally give a bit poorer scores when compared to the Decision trees.

Way forward:

deep dive in the significance of the used features
add new features (like winning streak, direct head2head comparisons, home advantage, ...)
use RL (yes I know, they would need to start playing again to make use of this one)