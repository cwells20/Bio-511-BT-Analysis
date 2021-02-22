# Bio-511-BT-Analysis

This .csv file contains data on the fecundity, weight, and length of bull trout specimens. These data were collected from authors, publicly available articles, and through my own work with Dr. Scholz.

I plan to use GLMs (likely Poisson regression) to model the relationship between bull trout weight and fecundity. I also want to model bull trout lengths against fecundity. I hope to be able to compare the models to determine the best possible model for predicting bull trout fecundity in a non lethal manner. 

Not included in this .csv are more data points for length and fecundity from other studies, but no others studies also included weight. I was hoping to make a model that could predict bull trout fecundity for any fish length and, by extension, any life history form a bull trout exhibits. 


Update for 2/21/21 Project Proposal assignment

With these weight, length, and egg count data from bull trout, I plan to attempt to answer whether weight or length are better predictors of fecundity in bull trout. I also hope to make reliable models for both so that eith could be used to estimate fecundity in a non-lethal manner. 

I plan to use a Poisson regression to model these relationships. While length or weight are not exactly categorical variables, I do think that a Poisson regression would work best as fecundity is a count and each fish counted is independent of one another. The relationship is also not linear, so I know a regular linear regression would not fit the data properly.

Predictor varaibles: total length (mm), fork length (mm), weight (g)
Response variable: fecundity (number of bull trout eggs)

As stated before, using a Poisson requires the assumptions that the response variable is count data. It also requires all of the observations to be independent of one another.

Based on some exploratory work in excel, I expect to see the model output an exponential curve with a positive slope. I expect both length and weight relationships to be significant. I am hoping to get high R^2 values, meaning the models will fit the data well. I will also get AICc values for the differnet models and use this to compare the different models and determine the best one (lowest AICc).
