# sentiment-analysis

In this project i worked on twitter uS airline sentiment dataset which is available in https://www.kaggle.com/crowdflower/twitter-airline-sentiment.

dataset has 14640 tweets with some properties that i just used text of tweets and labels.labels has 3 type:
a)positive
b)neutral
c)negetive

So i changed this labels to 1,0,-1 in order.For embedding,I did 2 solutions,at first i made embedding with keras and after that i used glove pretrained embedding 
glove.6B with 300 dimention.

For model i used cnn and lstm which lstm worked better than cnn.Finaly i used grid search to find best parameters.because it taked too long so i wrote the code but
i did not perform it.
