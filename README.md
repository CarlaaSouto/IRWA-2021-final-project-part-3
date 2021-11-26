# IRWA-2021-final-project-part-3

In this part we implement different Ranking algorithms to our dataset of tweets. The Ranking part is added to the part 1 and part 2. The code is a notebook, and to use it we only need to execute all cells.

The necessary imports are at the first cell, and for this part of the project we need to install the libary gensim in order to make the final plots.

For the first section of ranking, we create a new ranking score calculated using the following formula: TFIDF + c * (a * likes + b * retweets), where c is a normalization term. And a and b will determine the importance in the score of the likes and retweets respectively.

And for the second section, we use the library Word2Vec for representing the tweets as vectors and then compare how similar they are to the queries. 
