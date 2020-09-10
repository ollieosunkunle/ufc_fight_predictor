# UFC Fight Predictor

## Description
Binary classification model to predict outcome of UFC fights. Uses Scrapy to get fighter and event data from UFC.com and Pycaret for modelling/ensembling.

## Files
1. Fighter and event data stored in database/ufc_data.db
2. Methods are stored as functions in the methods folder including:
  1. Scraping code stored in scrape_bout_data and scrape_fighter_data
  2. Data wrangling and feature creation in clean_bout_data, clean_fighter_data and create_training_df
  3. Model creation with pycaret in create_training_df_model
  4. Test file creation (tbd)
3. Master_file will be used to call all functions in pipeline (tbd)  
