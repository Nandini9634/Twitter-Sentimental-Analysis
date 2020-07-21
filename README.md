# Twitter-Sentimental-Analysis

## Abstract

Sentiment Analysis refers to the use of Natural Language Processing to determine the attitude, opinions and emotions of a speaker, writer, or other subject within an online mention.A common use for this technology comes from its deployment in the social media space to discover how people feel about certain topics, particularly through users’ word-of-mouth in textual posts, or in the context of Twitter, their tweets.The user will be able to input a keyword and get the sentiment on it based on the latest 100 tweets that contain the input keyword.

## Dataset Used

1. Training dataset(train_tweets.csv)
2. Testing dataset(test_tweets.csv)

## What I have done

1. Imported python libararies and dataset.
2. Text pre-processing( Stopwords removal, Tokenization, Normalisation)
3. CountVectorizer, Tf-idf transformer to build weighted scores.
4. Model used : Multinomial Naive Bayes
5. Pipeline model to save the model.

## Results

Accuracy of the model is 94.1%
