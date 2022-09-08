# Second Problem statement: 
Create a classification model to predict the sentiment either (Positive or Negative) based on Covid Tweets

# Details of features:
The columns are described as follows:
1. UserName: UserName in encrypted numbers
2. ScreenName: ScreenName in encrypted numbers
3. Location: Country from where tweet was pulled from
4. TweetAt: Twee time
5. OriginalTweet: Tweet content
6. Sentiment: Positive, Negative, Neutral, Extremely Positive, Extremely Negative

# Solution presented

1)Read the dataset with encoding parameter set to ‘latin1’
2)Removed handle null values.
3)Preprocessed the Covid tweets based on the following parameter:
a) Tokenizing words
b) Convert words to lower case
c) Removing Punctuations
d) Removing Stop words
e) Stemming or lemmatizing the words
4)Converted the 'Extremely Positive' and 'Extremely Negative' Sentiments to 'Positive' and 'Negative' sentiments respectively
5)Transform the words into vectors using Count Vectorizer.
6)Splited data into training and test data.
7)Applied the following models on the training dataset and generate the predicted value for the test dataset
a) Multinomial Naïve Bayes Classification
b) SVM Classification
c) KNN Classification
8)Predicted the Sentiment for test data
9)Computed Confusion matrix and classification report for each of these models
