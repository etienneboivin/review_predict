# review_predict
Using machine learning to predict the number of stars in a Yelp review based on the review text.

This machine learning project uses a subset of the [Yelp Academic Dataset](https://www.yelp.com/dataset).

It uses scikit-learn to build a transformation pipeline that processes the text into a sparse NumPy array, then uses logistic regression to assign each review a score from 1 to 5, based on the sentiment of the review text.
