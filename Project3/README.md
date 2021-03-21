# Project 3: Web APIs & Classification

### Problem Statement
Reddit is a collection of online discussion boards known as "subreddits", which cover a variety of topics including links, text posts, and images, which are then voted up or down by other members. The goal of this project is to classify which subreddit a given post came from. As there are over 1.5 million subreddits on reddit, we will be classifying posts from two subreddits, [/r/AppleWatch](https://www.reddit.com/r/AppleWatch/) and [/r/GalaxyWatch](https://www.reddit.com/r/GalaxyWatch/).  We will be creating and comparing three models: a logistic regression, multinomial naive Bayes classifier and Random Forest Classifier in order to find what characteristics of a post in Redit contribute to what subreddit it belongs to and also find the top classifiers.

### Executive Summary
The key tokens of r/AppleWatch includes series, se, aw, iphone, month, activity ,loop, calorie, siri, ring, nike, like, watchos, cellular, blue, challenge, today, complication and workout.

The key tokens of r/GalaxyWatch includes active, samsung, gw, bezel, gwa, gear, update, phone, lte, tizen, find, button, face, samsung health, anyone, bixby.

People from these apple watch subreddit seems to discuss a lot about the recent models, latest features and also discuss their daily usage with health monitoring. Also, people talk more about the monthly challenges, exercise ring, workout app and activity app in r/AppleWatch subreddits. The most popular ring feature also became a top classifier along with 'blue' keyword(representing Stand). Loop model also topped in the classification due to its excellent review than Sport band and buckle models.

Whereas people in r/GalaxyWatch talk more about featires such as OS,updates, bezel and buttons. There seemed to be issue with the galaxy watch buttons which was reflected in the posts and hence appeared in top classifiers of galaxy subreddit.

Both subredditrers are also interested in cellular/lte models thus contributing to top classifiers.


### Conclusions and Recommendations
We could see that the two subreddits were able to classified with 90% accuracy and also there seemed to be quite a bit of overfitting.Three classification models were used for evaluation of the corpus - Logistic , Random Forest and MultinomialNB. The Logistic approach we get coefficients that estimate how our independent variables(text features) affect our dependent variable(correct subreddit). It therefore is a very good model to use because the dataset is not very big and the model is not being overwhelmed by many features.

The Logistic Regression with TFIDF Vecotizer is our best performer followed by Random Forest with TFIDF. Further explorations should include using: A boosting algorithm for classification like AdaBoost or Gradient boost. Collecting more and reevaluate the performance of models with additional stop words after model iterations and also ensemble trees with bagging and boosting.

The findings can be used by companies or the users to better understand the top features the people are discussing and further sentiment analysis on this data could be used to find the positive or negative review about the watches.


