### project-4-twitter-sentiment
Overview
# Project 4 - Twitter Sentiment
## Overview/Business Understanding
I have been tasked by our companies stake holders to create a model that can classify tweets as positive as a first step towards helping our marketing department see the effects of their marketing strategies. The scope of this project is that first step

## Data Understanding and Analysis
Data is taken from [data.world](https://data.world/crowdflower/brands-and-product-emotions/workspace/file?filename=judge-1377884607_tweet_product_company.csv). According to their website "Contributors evaluated tweets about multiple brands and products. The crowd was asked if the tweet expressed positive, negative, or no emotion towards a brand and/or product. If some emotion was expressed they were also asked to say which brand or product was the target of that emotion. Added: August 30, 2013 by Kent Cavender-Bares | Data Rows: 9093" In other words, this data was manually classified as either Positive, Neutral, or Negative manually and now can be used to train a model to determine if a tweet can be classified as positive.


### Visualizations used in analysis
Confusion Matrix of Final Model
![confusion-matrix-MB](images/confusion-matrix-MB.png")

## Evaluation
Evaluation
Our Multinomial Naive Bayes model is able to accurately predict if a tweet is positive 66% of the time, more importantly it has 62% precision. This is a good 4% better than our initial baseline Decision Tree Model.

We care most about precision because tweets that are classified as positive but are actually negative are more hurtful to our marketing than losing a little bit of insight from classifying a tweet as negative that is actually negative.

## Conclusion/Recommendation
Use the model here to help classify positive tweets that we can then be used to gleen further insights from tweets related to our marketing department to improve our strategies and find key words and products that people enjoy

### Navigating the Repository
* data
* images
    * confusion-matrix-MB.png
* .gitignore
* README.md
* project-4-positive-tweet-classification.ipynb
* project-4-presentation

### Link to Presentation
![film-analysis-presentation.pdf](https://github.com/jaredlil/Phase_2_Project_Film/blob/main/film-analysis-presentation.pdf)
### Link to Blog
https://datasciencedigested.blogspot.com/2024/08/wasted-time-and-effort.html