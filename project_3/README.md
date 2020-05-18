# Project 3: Web APIs & Classification

### Description
For project 3, your goal is two-fold:
1. Using Reddit's API,  collect posts from two subreddits of choice.
2. Use NLP to train a classifier on which subreddit given post came from. This is a binary classification problem.


#### About the API

Reddit's API is fairly straightforward. For example, if I want the posts from [`/r/boardgames`](https://www.reddit.com/r/boardgames), all I have to do is add `.json` to the end of the url: https://www.reddit.com/r/boardgames.json

### Requirements

- Gather and prepare your data using the `requests` library.
- **Create and compare two models**. One of these must be a Bayes classifier, however the other can be a classifier of your choosing: logistic regression, KNN, SVM, etc.
