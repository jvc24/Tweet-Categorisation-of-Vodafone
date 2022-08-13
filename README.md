![image](https://user-images.githubusercontent.com/63221994/184503015-3fc7a373-84b0-41da-9d36-f4a4a4f2b2ca.png)

# Tweet-Categorisation-of-Vodafone
Given a tweet build, train and deploy Machine Learning model which will extract data from twitter and will classify tweets according to different types of emotions/ topics.



## Situation 
- Vodafone is 3rd Largest telecom company in India
- Tweets are frequently used to express a tweeter’s emotion, opinion or any complaints on any particular subject.
- Problems faced by the customers are tweeted every day which are need to be addressed to improve service.

## Constraints
- Manual work is required to identify the problem.
- More man power (more investment which unrequired )
- Time Consuming

![image](https://user-images.githubusercontent.com/63221994/184502399-ca075e47-d1a2-4382-ab65-fc3e4a3c6f6b.png)

## Process Flow
![image](https://user-images.githubusercontent.com/63221994/184502432-f32e97ec-d762-4694-94db-f52998c22b7d.png)

## 1) Extracting tweets
Twint uses the classic Twitter search and can thus retrieve all the tweets from an account. It can even retrieve only those containing the keyword of choice, or those posted between such and such a date, or from such and such a place, or only the retweets. It is also possible to retrieve all tweets from all Twitter accounts that mention the keyword of your choice. It automatically saves the data scrapped into a csv file named tweetsfromvodafonin2. Using this we scrapped all tweets of keyword vodafonein. About 20k tweets were scrapped using the following code

## 2) Data Cleaning:-
1. Removed all the stop words
2. Removed all the punctuations
3. Used word2vec model to vectorise the words.

## 3) K-Means:-
1. Used K-means clustering to cluster the data.
2. Divided the whole data into 8 clusters



