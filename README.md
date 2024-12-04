# Project_4: Life Expectancy Model
This project will work to train a model to predict life expectancy in the future based on information provided about the past. Information provided to the model will include, country, life expectancy (by year), GDP, population, exposure to a variety of diseases, and many other factors. 
The raw data will first be sourced and put into a SQL data frame to make the data cleaning process more efficient. 
The data will be cleaned as some of the raw data is inaccurate or missing. For the ease of training the model, a new column will be created during the data cleaning step. This new column will combine Country and Year. This new column will be what is used to train the new model. 
Once the data has been cleaned the data will be modeled using XGBoost. During this process the data will be split into X and Y variables. The size of the model data will be calculated and then the model will be trained. Once complete, it will be evaluated for its accuracy and iterations or changes will be made if the model does not meet pre-determined accuracy goals. 
One additional goal for the project would be to make the model interactable with a command line prompt. This would allow the end user to enter a prompt and predict life expectancy with the trained model based on user-provided inputs. 

Project Overview: 
Data Retrieval - James
Data Cleaning - Laura and Jane 
Data Modeling - Rob and Ross

Data Limits: 
Adult Mortality Lower Limit: 200 per 1000
Under 5 Lower Limit: 65 per 1000
Infant Death Lower Limit: 27 per 1000

Data Source:
https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?resource=download

Other Tasks:
PowerPoint Slides: James, Jane, Laura, Rob, & Ross
ReadMe: Ross 
