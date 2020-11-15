# machine-learning-challenge
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. In this challenge, I created three machine learning models capable of classifying candidate exoplanets from the raw dataset, to help process this data.

I started with a logistic regression model. The score for the non-scaled vs scaled data showed better result on the  non-scaled, still around 68% for the test data. For this reason a grid searh was performed, using "C" and "penalty" for the hyperparameter tuning. This improved the model showing a prediction score of 87.9%. 
The second model is a Support Vector Machine. Training the model showed best results with the scaled data. "C" and "gamma" were used in the hyperparameter tuning. The prediction score is the same for this model, 87.9%. This was surprising, even after changing the random_state to 12, got the same result.
Lastly, I decided to try a Random Forest for any possible improvement. This doesn't require feature scaling. It scored 90.2% and would be the selected model for prediction.
After this submission I would be trying deep learning for further exploration.
