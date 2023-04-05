This project is done following Coursera: Natural Language Processing with Classification and Vector Spaces course's week 1 graded assignment.

"NLP_sentiment_analysis_preprocessing.ipynb" contains the steps of preparing a single tweet for any machine learning model. Steps contain tokenization, stemming, removing stopwords and punctuation and so on.

"utils.py" has two functions, process_tweet and count_freqs. process_tweet is a function that take a single tweet as input and give list of clean tokens of that tweet. The second function creates a dictionary of all the words and map (word,class) to frequency.

"Visualize_logistic_regression_model.ipynb" helps us to visualize the logistice model by plotting the features of all  the tweets and a separation line between them. "logistic_features.csv" file has the pre calculated positive and negative features that are used to visualize the model.

"Sentiment_analysis_LR_main.ipynb" is the main code that use Logistic regression model for sentiment analysis. It has a test accuracy of 99.5%.


"bayes_features.csv" contains the  calculated the likelihood of the tweet to be positive and the likelihood to be negative. This file is used in "Visualize_naive_bayes.ipynb" code.

"Sentiment_analysis_with_naive_bayes.ipynb" code has all the steps of classifying a list of tweets into positive and negative classes. It has a training accuracy of 99.55%.