# insurance_model

The purpose of this work is to estimate the probability that an individual (seeking auto insurance) will be in an accident and then to forecast the potential cost of an ensuing claim. A synthetic data set of ~ 8000 observations will be used to construct predictive models for this purpose. The use of synthetic data permits model development absent proprietary information, while also providing a heuristic for quantitative reasoning

Completed Workflow:

* data preprocessing 
* logistic regression models 
* log-normal and gamma models 
* summary 

Results:

This study sought to classify drivers based on their probability of an auto accident and to then predict the amount of claim payout associated with that accident. The covariates provided in the dataset were sufficient to build/select an effective logistic classifier. Predicting claim payout proved more problematic - owing to the small number of covariates suited for individual payout predictions as well as lack of information on how payment amount was derived. 

Project Publication: https://rpubs.com/sconnin/856781

insurance_model.Rmd = project code 

insurance_dataset.csv = raw data

base_df.csv = processed data 
