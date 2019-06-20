# Board-Game-Review-Predictor

## Aim
Predict the average_rating using other columns of data using Linear Regression Model and Random Forest Regressor.

## About the Dataset
 The dataset was scrubbed from a database from BoardGameGeek of 80,000 board games and includes information such as minimum players, maximum players, minimum playtime, maximum playtime, etc and can be found here.
 https://github.com/ThaWeatherman/scrapers/tree/master/boardgamegeek
 
## Observation
 We do not need bayes as based on average rating, average rating is in training set, we also remove type,name and id.
 
 Since the dataset contained a few missing values and there were rows without reviews, where there is a score of 0, we removed it.
 
### Conclusion
After using Linear Regression Model the mean squared error came out to be 2.0973417688243936 making it unfit for this prediction
thus I tried Random Forest Regressor which gave me a mean squared error of 1.451531643042825 and gave predictions **closer** to 
the actual value of ratings by a tiny fraction.





