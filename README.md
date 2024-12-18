# Project_4: Life Expectancy Model
This project will work to train a model to predict life expectancy in the future based on information provided about the past. Information provided to the model will include, country, life expectancy (by year), GDP, population, exposure to a variety of diseases, and many other factors. 
The raw data will first be sourced and put into a SQL data frame to make the data cleaning process more efficient. 
The data will be cleaned as some of the raw data is inaccurate or missing. For the ease of training the model, a new column will be created during the data cleaning step. This new column will combine Country and Year. This new column will be what is used to train the new model. 
Once the data has been cleaned the data will be modeled using XGBoost. During this process the data will be split into X and Y variables. The size of the model data will be calculated and then the model will be trained. Once complete, it will be evaluated for its accuracy and iterations or changes will be made if the model does not meet pre-determined accuracy goals. 
Additionally, from this data we plan to identify and show which factors contribute most to life expetancy.

Project Overview: 
Data Retrieval - James
Data Cleaning - Laura and Jane 
Data Modeling - Rob and Ross

Data Source:
https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?resource=download

Other Tasks:
PowerPoint Slides: James, Jane, Laura, Rob, & Ross
ReadMe: Ross 
