# BT4222 Sentiment Analysis Group 7
Sentimental Analysis with the Financial Market

# Filepath Description

## CNN-LSTM-Attn/
Contains our groups attempt at utilising CNN LSTM Attn Model. Eventually we decided to proceed with focusing on Stacking method on lightweight models due to the higher accuracy score and its lower resource intensiveness.

## experiments/
Contains the various experiments that the team ran while trying to test out different features for the machine learning model pipeline.

## dataset/
Contains different versions of processed dataset(s) that the team used for model training.

# File Description

## saved models/models_desc.txt
Contains the link to our final models and vectorizer (for feature engineering).

## experiments/Simple_ML_Models.ipynb
Contains all the experiments done on models from the sklearn library. These include experiments to test out different classification models, hyperparameter fine-tuning, and model aggregation algorithms. The findings here form the basis for many of the decisions made regarding the final model architecture.

## experiments/FE_NGram.ipynb, experiments/Feature_Engineering.ipynb, experiments/Copy_of_Simple_ML_Models.ipynb
All 3 files were used to try out different feature engineering techniques for our model input, as well as NER methods to identify the entities in each data point.

## experiments/Data_Preprocessing.ipynb
Contains data pre-processing code to combine and clean the data.

## Final_Model.ipynb
Contains data pre-processing, feature engineering, model training, hyperparameter fine-tuning, and model testing pipeline. It is a summary of what we have found to be the most effective in each aspect of the pipeline. It also does the final evaluation of our final model using the test data. 

## error_analysis.ipynb
The file performs error analysis on a machine learning model to gain insights into its performance. The analysis includes visualizations such as word clouds and the percentage of wrongly predicted values.


