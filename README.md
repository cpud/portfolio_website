# Cam's Portfolio

[Covid-19 Tweets Sentiment Classification](https://www.kaggle.com/campudney/covid-19-tweets-eda-classification-bert/)
+ Tested multiple models and NLP techniques to compare classification accuracy of tweets with ‘covid19’ hashtag
+ Models included Support Vector Machine, Logistic Regression, Naive Bayes, Random Forest Classifier, BERT
+ Utilized NLP techniques such as Term Frequency Inverse Document Frequency, Stemming, and Lemmatization
+ Combinations of models and techniques compared using accuracies generated from 10-fold cross validation
+ Support Vector Machine using Term Frequency Inverse Document Frequency was the best ‘traditional’ model and yielded an 80% percent accuracy on training data and 79% accuracy on testing data
+ BERT trained on the tweets boasted an 85% accuracy on testing data after minimal  hyperparameter tuning

![](images/covid.png)

[Rock Climbing Routes In The US](https://www.kaggle.com/campudney/rock-climbing-routes-in-the-us)
+ Created visualizations of rock climbing routes using data scraped from MountainProject with BeautifulSoup4
+ Plotly choropleth map displays number of climbing areas and amounts of different types of climbing by state
+ Animated choropleth map allows user to select type of climbing to be displayed
+ California and Colorado have the most routes, but Massachusetts and Wisconsin have more than expected
+ [Final visualizations found here:](https://github.com/cpud/climb-plotly/blob/master/final2.ipynb)
+ [All code for scraping found here](https://www.kaggle.com/campudney/rock-climbing-routes-in-the-us)


![](images/climbing.png)
