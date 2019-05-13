# Early-Predictions-of-Movie-Success-using-Social Media

- Author: Yang Liu, Shuqiong Chen, Jingchen Lan, Jiawei Xue
- Contact: yliu249@stevens.edu, eric.liu.249@gmail.com
<br>


## Introduction<br>

In 2018, the global box office revenue hit 41.7 billion U.S dollars. In U.S, the number amounted to about 11.9 billion U.S. dollars. United States alone released more than 800 movies in 2018. However, only a small number of movies have high return on investment. Most of them have very limit life time and are dethroned as new starlets are not long in coming. For movie investors, they want to know whether their investment will ultimately lead to returns or profits when the movies are officially released. For film studios, they want to optimize their arrangement of movies by predicting the box office. Knowing which movies are most likely to success and which are most likely to fail could benefits investors and film studio a lot. It could also help them to release movie in a most appropriate way. 

We collected the early period review of movies from IMDB and used Natural language processing (NLP) tools to conduct the movie review analysis. Sentiment analysis will be used to find out people’s views about films. The definition of a movie success is relative, some movies are called successful based on its worldwide gross income, and some movies may not be outstanding in business part but can be called successful for good review and popularity, while we believe the business values is always the key point for marketers and investors, so we will use return on investment (ROI) as our target variable. A movie that ROI>1 is regarded as a business successful movie, and vice versa.

As the most popular review hubs, we chose IMDb as the mainly resources for our project dataset. The dataset concludes following information: score, review number and review content, user rating, average rating, director, stars, genres, box office, budget, release date. We first built a baseline model based on movie category features, then we applied text analysis to generate more feature from the early review. 

We use the largest number of box office a director/actor has earned through his/her career before the predicted movie is released to quantify person’s value. Most of the research work related to the prediction of movie success use social network analysis to analyze the relationship between different person. They also implied sentiment analysis to gain insight from user’s review, but they haven’t generated related feature from review text to predict the success of movie box office directly. We imply two method to quantify film’s and person’s value through text analysis. We first used naïve method to count the frequency of person’s name in review text, then we use word2vector to expand the clue words from aspect clue words table. We also used review text to predict the user’s rating.
