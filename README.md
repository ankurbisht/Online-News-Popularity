# Online-News-Popularity
With the expansion of the Internet, more and more people enjoy reading and sharing online news articles. The number of shares under a news article indicates how popular the news is.  Our data comes from Mashable, a well-known online news website. 

# Objective:
We will provide recommendations to increase popularity of any article by tweaking some of the charateristics like number of words, number of images  of the article.Our work can help online news companies to improve news popularity before publishing it.
  
# Steps:
<li>We implemented different learning algorithms on the dataset, ranging from various classification technique like Logistic Regression, Decision Tree ,Random Forest & other Tree Boosted Models. 
<li>Their performances are recorded and compared. 
<li>Feature selection methods are used to improve performance and reduce features.

# Final Model Predictions
![alt text](https://github.com/ankurbisht/Online-News-Popularity/blob/main/Score.png?raw=true)

### LightGBM Forest turns out to be the best model for prediction, and it can achieve an auc score of 73.4% with optimal parameters.

# Recommendations
<li>Restrict article word length to 2500 words
<li>Number of embedded links should be in range 0-25
<li>Number of images should be in range 0-10. Lesser the better
<li>Number of videos should be between 0-5. Lesser the better
<li>References to older articles which have high popularity
<li>Publish articles on weekend
<li>Focusing more on Entertainment or Lifestyle articles can get you popularity
