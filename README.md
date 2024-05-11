# spring2024-data698
DATA 698 Capstone Project

Author: Kory Martin  
Date: 5/11/2024  
LinkedIn: https://www.linkedin.com/in/korylmartin/

## Introduction
This project is focused on developing a prediction model that predicts a voters support or opposition to a ballot initiative based on the explainer text provided for the intiative and the demographic profile of the individual voter.

## Requirements.txt
The requirements.txt file for this project is stored in the git repo

## Links to Files
The following are links to the various files that were used to create the final data files. 

Raw Files
1. [Raw Files](https://data698-capstone-project.s3.us-west-2.amazonaws.com/raw_files/)

Precinct Data
1. [Combined precinct mapping info](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/precinct_info.parquet)
2. [Population percent by Precinct](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/precinct_percent_total.parquet)
3. [Voter Support or Opposition by Precinct](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/voter_selection.parquet)
4. [Precinct to Census Tract Mapping](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/precinct_census_mapping.parquet)
5. [Demographic Info by Precinct](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/precinct_demo_info.parquet)
6. [Demographic Percentages by Precinct](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/precinct_demographic_percentages.parquet)
7. [Precinct demographic totals](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/precinct_demographic_totals.parquet)
8. [Total Demographic Percentages](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/demographic_percentages.parquet)

Text Corpus:
1. [Text Corpus](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/combined_df_final.parquet)

Census Data:
1. [Available Block Groups](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/block_group_census_variables.csv)
2. [List of Census Features](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/census_features.parquet.parquet)
3. [Demographic Totals by Census Tract](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/census_features_total.parquet)
4. [Census Rows from AC5 API](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/census_rows_df.parquet)

Training Data:
1. [Training Data Full](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/model_training_data.parquet.parquet)
2. [Training Data Mini](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/model_training_data_mini.parquet)

Classifier Models:
1. [Ada Boost Classifier](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/ab_classifier.joblib)
2. [Bagging Classifier](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/bag_classifier.joblib)
3. [KNN Classifier](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/knn_classifier.joblib)
4. [Logistic Regression Classifier](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/lr_classifier.joblib)
5. [Naive Bayes Classifer](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/nb_classifier.joblib)
6. [Neural Net Classifier](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/nnet_classifier.joblib)
7. [Random Forest Classifier](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/rf_classifier.joblib)

Text Vectorizers:
1. [Count Vectorizer](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/count_vectorizer.joblib)
2. [Term Frequency Vectorizer](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/models/tf_vectorizer.joblib)

User Response Data:
1. [Raw User Resposnes](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/user_responses.csv)
2. [Mapping File to clean Response Data](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/response_mapping.csv)
3. [Clean User Responses](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/user_responses_clean.parquet)
4. [Analysis results of user responses](https://data698-capstone-project.s3.us-west-2.amazonaws.com/clean_files/user_responses_analysis.parquet)
