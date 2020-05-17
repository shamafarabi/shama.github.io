---
layout: default
mathjax: true
comments: true
title: Data science projects
permalink: /dataprojects/
---
## Projects
### 1. Predict Cast Member of the show "Friends" - [repo,](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP) [blog](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/Project%20Report.ipynb)
This project demonstrates use of NLP to be able to identify movie/TV show characters from any line they have said in the show by using the transcripts of the show as the source of dataset for different ML models. I used the popular TV show 'Friends' as the test case. I webscraped text transcripts of 235 episodes of Friends and processed the data in a dataframe with 489,44 observations such that the lines said by different cast members can be used as input to train different ML models.

I implemented interactive visualization to identify insights about the members and investigate potential challenges of ML modeling (e.g. class- imbalance). Then I applied different word embedding techniques (count-vectorizer,tf-idf, word2vec etc.) to convert the lines in the observation into features and identified tfidf to be the best candidate. Next, I applied different ML (multinomial naive bayes, logistic regression, support vector machines) and DL models and evaluated their prediction performance based on accuracy,confusion matrix and class specific roc_auc score. Finally, I utlized different reasmping techniques to address class imbalance and performed feature engineering to improve model prediction.

### 2. Predict Users Ratings and Recommend New Books to Read - [repo,](Book_Recommendation_Engine)[blog](https://nbviewer.jupyter.org/github/shamafarabi/Capstone_1_Book_Recommendation/blob/master/Milestone%20Report/Milestone%20Report.ipynb)
Book reading apps like Goodreads has personally helped me to find books I couldn’t put away and thus getting back to the habit of reading regularly again. In this project, I developed a collaborative filterning based book recommendation model using goodreads dataset that can suggest readers what books to read next. 

Utilizing exploratory data analysis on  6,000,000 user ratings, 10,000 books and 34,252 book tags, I identified business insights  about goodreads users reading preferences (e.g. how they like to tag books, what ratings they usually provide etc.) and current trends in the book market (book categories that are in demand, successful authors in the market etc.). Then I utilized ML models (KNN, SVD and NMF) to predict user ratings to books they are yet to read. The recommendation engine is capable of making base-case recommendations for new/anonymous users based on the average book ratings and/or other keywords, and personalized recommendations to an active user based on his/her activity history and search preferences. The search engine also has smart filterning capabiliy (e.g. it can recommend books from JK Rowling and Rainbow Rowell if user search by the keyword "row')and can provide built in tag-recommendations\suggestions to further refine the search.
