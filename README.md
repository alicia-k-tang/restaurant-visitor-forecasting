# visitor-forecasting

**This README only offers a brief overview of the assignment. Further analysis containing graphs and literature review can be found in "Recruit Restaurant Forecasting Analysis" file of this repository.**

## Introduction
For this class assignment, we were tasked with participating in [Kaggle’s Recruit Restaurant Visitor Forecasting](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting)
competition. The context of the competition is set in Japan, where participants
were given restaurant and visitor data in order to predict the future number of daily visitors.
Knowing this information provides an incredibly valuable tool for restaurant businesses. In
particular, accurate visitor predictions could aim to help with one of the most uncertain aspects
of the business— how to prepare.
Being ready for the amount of customers that come in each day include purchasing the
correct amount of stock, where no more and no less is used, as well as scheduling enough
workers for the day. It is difficult to prepare these things without knowing the number of visitors.
Better preparation, in turn, increases the overall efficiency for restaurants. Once the proper
number of resources are determined, more effort can be focused on brainstorming ways of giving
consumers a better experience— one without any sort of delay in service, and one with a better
dining aspect. Accurately predicting the number of visitors leads to a win-win situation for both
restaurants and consumers, making it an important problem to analyze. 

## Data
Ultimately, being presented wth many datasets at once was overwhelming. One of the
biggest challenges for me was choosing the best datasets that would give me useful information
in predicting visitors accurately. In the end, I only chose to examine the AirRegi datasets with
air_visit_data, air_store_info, and date_info. I did not choose to look at any Hot Pepper Gourmet
(HPG) datasets, because I did not think it would offer a substantial amount of improvement to
our model. This is because if we only look at HPG reservations, the amount of reservations do
not always equate to visitors. Customers can easily cancel reservations or simply not show up.
For these reasons, I was more curious in examining datasets with the official number of visitors,
the visit date, and the store information. I also decided to use the dataset concerning holidays,
because the dates that we have to predict (April 23rd - May 31st), falls within the timeframe of
Japan’s Golden Week. Because of this, it was crucial to also examine the relationship between
holidays and number of visitors.


## Concluding Thoughts
Overall, this competition was difficult but fun to explore. I enjoyed applying the skills
and methods learned from class to real-world situations— which is hard to conceptualize at
times. Finding the best model for forecasting was challenging, but I also learned and was able to
see how differently models perform on training and unseen data. Though the ARIMA and Neural
Networks models performed substantially better on the training data, the ETS model outshined
the others on the testing data. It was compelling to be able to see how this could be possible
firsthand.
If I reattempted this competition in the future, I would improve my model by including
more relevant datasets and trying other forecasting methods. I focused more on ARIMA, ETS,
and NN models for this assignment, but there are many other models I could have tried. I would
be interested in using the Holt-Winters or Prophet method next time. Additionally, I would have
included the different types of cuisines in my model. To do this, I would create a model for each
genre of cuisine and adjust it in accordance. It would have been fascinating to examine the
intersection between certain trends at the time and different genres of food and see if this would
affect visitor counts for certain restaurants.
