# Machine Learning in Mergers and Acquisitions

This projects leverageas **machine learning to predict the deal price of Mergers and Acquisitions (M&A)**

For my master thesis in my appliead economics I investigated the use of machine learning in M&A.
After consulting the literature I developed my own models to predict the deal price of mergers and acquisitions.
More specificly I predictied the deal price for startups using non-financial data.

The crunchbase 2013 snapshot dataset was used to compare *neural networks* to *linear regression, support vector machine and XGBoost*.

**Results** show that neural networks and XGBoost perform better than simpeler models.
Next to that, non-financial data seems to be valuable in predicting the deal price of M&A.
This indicates that, with improved data, machine learning can be a valuable addition to mergers and acquisitions



## Notebooks
Several notebooks have been written to complete this project.
- The *data_gathering* notebook contains the selection of tables, columns and rows from the crunchbase 2013 snapshot
- Data cleaning and exploratory analysis is conducted in the *feature_engeneering_and_exploration* notebook.
- The *feature_engeneering_dummy* notebook contains code to translate numeric variables to dummy-variables. This was tested to see if it improves results.
- The linear regression, support vector machine and XGBoost are trained in the *modelling* notebook. The neural network was trained in the *deal_price_prediction_NN_keras_tuner* notebook
- Model performance was analysed in *model_performance* and *model_performance_NN* for the machine learning and deep learning models respectively
