# Project 5. Car price prediction
##### Done by Alena Kurylchyk and Marina Bovkush as BK_Team
##### LB MAPE %, ranking is .

## Project objective ##
We need to build a model that can predict car's price by its features.

## Project features ##
1. We don't have a ready dataset, so we have to parse auto.ru website to collect information for machine learning.
2. The metrics that will evaluate the quality of the model is MAPE (mean absolute percentage error).'

## Requirements ##
1. Project should be done by a team.
2. Parsing code should be presented (in kaggle notebook or uploaded to github).
3. Project code must be presented on github and kaggle.
4. MAPE metric for the final model must exceed baseline's result.
5. Predicted price values must be submitted to kaggle, the result from the leaderboard must be presented on github.

## What has been done ##
0. Gathering of a team.
1. Data enrichment.
+ Parsing of relevant data from auto.ru.
+ Unification and merging of test and parsed datasets.

2. EDA
+ Quick dataset overview using profile report.
+ Handling of duplicates.
+ Handling of missing values.
+ Visualisation of features distribution and relationship with a target value.
+ Outlier analysis.
+ Dividing features into categories.
+ Analysis of relation between features categories and with a target value.

3. Feature Engineering
+ Two new features have been included into dataset.

4. ML
+ Encoding of all binary and categorical features.
+ Testing of 5 different models: Random Forest, CatBoost, Gradient Boosting, XGBoost, LightGBM. Bagging and stacking have also been tested.

## Results ##
+ Standartisation of numeric variabled hasn't given quality increase thus hasn't been used.
+ The best result was shown by Stacking of Gradient Boosting and XGBoost.
+ The best MAPE metric on the leaderboard is  .
+ The leaderboard ranking is  .

## What could be improved ##
+ Perfoming of feature engineering.
+ Trying some NLP methods to extract useful data.
+ Better hyperparameters tuning.
+ Testing of other models (i.g. ExtraTrees).
+ More deep analysis of the data and the results to understand what impacts MAPE the most.

## Retrospective ##
+ The project is too massive to be done within a week.
+ The team had a lot of issues with kaggle and parsing and has wasted a lot of time on solving them.
+ Time for Feature Engineering had to be reduced due to deadline.
+ The work has been very stressful under such conditions, the team is not satisfied.
