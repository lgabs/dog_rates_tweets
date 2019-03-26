# Dog Rates Analysis

## Exploration of tweets about dogs from @dog_rates twitter account (project in Udacity Data Science II Course)

In this project, we interact with Twitter API (`tweepy` library) to gather data about a dog account called "dog_rates", which rates dogs with brief explanations and an image. The given table `twitter-archive-enhanced.csv` has some information about each tweet, including the rating for each tweet/dog. Another given table `image_predictions.tsv` provides the predicted breed for each dog (this prediction was already done). Both tables have `tweet_id` as a reference, and this column is used to pull more information from Twitter API. All data is then gathered in one unique table and a analysis is conducted, including cleaning steps (quality problems and tidiness problems).

With a clean and tidy table, we raise some interesting questions to understand the dog ratings and their breeds, like:

1.  How many dog races do we have in our table? List the top 5 races that got more favorites and the top 5 for those that got more retweets. 
2. Are there many duplicates for names? What's the most common name? 
3. How these tweets were posted through time? Plot number of tweets per day, per month and per year. 
4. What's the distribution of rating_numerator (min and max values, average etc)? 
