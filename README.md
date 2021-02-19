# What's the improvement

This part aims at discovering if feature engineering helps to model improvement.

Analysed the correlation between variables, reduced the number of variables from 46 to 19. Coefficient for categorical data -- Cramer'V

Convert continuous data to categorical data which showed clearer linear relation between predictors and target variable.

Permutation Feature Importance to avoid bias on categorial feature

Upsampling for more models -- a brief experiment

##  More thoughts about modelling:
Considering LightGBM?

Ensemble and stack promising models?

Do some segmentation on important categorical features as contract type"

##  Thoughts about business:
Prediction just a part of "churn" topic, in terms of marketing campaign, keeping all risk customers (predicted to churn) ? or take further step to estimate who might be more valuble customers, then the priority is to keep these more valuable customers? If you think some customers will churn anyway, then maybe save marketing cost?