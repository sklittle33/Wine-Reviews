# Wine-Reviews
Applying machine learning methods to a data set containing reviews on bottles of wine

In this presentation, we will be studying a data set comprised of wine reviews scraped from the Wine Enthusiast Magazine from 2017. The data can be found on Kaggle (https://www.kaggle.com/zynicide/wine-reviews) . 
The dataset consists of around 130,000 wine reviews written by critics with information on price, grape variety, place of origin, points and several other variables.The points score ranges from 80-100 and are classified into 6 categories according to the magazine. The magazine says it does not post reviews for wine scoring below 80.

# Question of Interest/ Hypothesis

Can we use machine learning methods to predict the points for a bottle of wine that has yet to be reviewed by the magazine given the other variables in the data set?

Hypothesis: Wine review scores can be predicted for unknown titles or wineries using a combination of other available variables and wine review sentiment analysis 


# The Methods 
We will look to build a machine learning algorithm which will predict one of the six score categories for wines with unknown titles or wineries by utilizing other available variables in the data set. We will first explore the data set in some detail to undertake necessary data cleaning and to determine which variables are useable based on the available data.

Then we will construct training and testing subsets from the full data set with points scores stratified by category, and perform some data visualization to evaluate each variable's usefulness in predicting wine score categories.

We then train QDA, LDA, classification tree, random forest,and SVM models on the training set and we will assess them based on their accuracy rate in determining correct points categories.

Finally, once we determine the model with the highest accuracy, we use it to make predictions our testing set, review its accuracy performance, and provide suggestions for improvements or next steps for further study.
