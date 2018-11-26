In the final project, you are asked to analyze the Russian Trolls NBC News Dataset.

Please perform the analysis that you proposed in the final project proposal.

The total points for the final project is 21pts.

 

Step 1: Loading data (3 pts)

Step 2: Pre-processing the tweets (8ptstotal)

            You can use one of the three recommended libraries for this task or NLTK.

Tokenization (2pt)
Lemmatization (2pt)
Stopwords removal
removing standard stopwords (2pts)
removing additional stopwords as you see fit (2pts)
 

Step 3: Data analysis (10pts)

Many mentioned tasks such as “search and count”, “sentiment analysis”, “named entity recognition”, “hashtag analysis”, and “topic modeling”. Note that tasks including “sentiment analysis” and “named entity recognition” should be performed beforepreprocessing for best result.

 

To be more specific, if you wish to do search and count on the Twitter dataset, you can choose a keyword or a group of keywords (you can use “AND”, “OR”, “NOT” here) that you are interested in.

 

If you wish to perform sentiment analysis, get the polarity result for each tweet and then you can choose how to aggregate the sentiment analysis results. One example is that you can aggregate on a daily basis. One recommended method to such aggregation is adding up the positive and negative polarities separately and then divide them by the total number of tweets on that day.

Required output:

Example tweets for each task you performed. For example, if your task is search and count with keyword “immigration”, print out 20 tweets that match your search. If your task is sentiment analysis, print out 20 tweets that have the strongest positive sentiment and 20 tweets that have the strongest negative sentiment. Printing out such results not only help us understand the dataset better, but also will help validating your python script.
2. If your task involves search and count, sentiment analysis, or named entity extraction, construct a timeline to demonstrate the trends over time (i.e. trends on keyword mentions, sentiment change, or entity mentions). One exception is topic modeling. If you wish to perform this task, you don’t have to construct a timeline for a topic.
