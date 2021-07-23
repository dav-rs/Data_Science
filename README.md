# Data Science Projects
This repo contains different projects related to the different areas of Data Science using Python, PySpark or R. The projects' focus is interpretation, predictive analysis or both. The following description gives general information about each project.
## Python
1. news_scrapper: Scrapping news from one of Australia's news websites. This project has an educational scope, and none of the data scrapped was used for any commercial purposes.
2. topic_modelling: Using the scrapped data as input, we use LDA (Latent Dirichlet Allocation) to group it into topics and analyze the results
3. EDA_melb_housing: Using a dataset containing information about Victoria Housing we focus on the Melbourne housing market and perform some EDA to gain some general insights about this dataset
4. classification_pySpark: This Jupyter notebook contains a classification model**(Gradient Boosted Trees)** for predicting hacking attacks on a dataset containing memory and process activity from Linux systems. (https://ieee-dataport.org/documents/toniot-datasets). 
5. recommendation_system: This notebook contains a recommendation system trained with PySpark using ALS for collaborative filtering. The data corersponds to the movie lens dataset, and the model is trained using a parameter grid for tuning and cross validation. At the end a function is included to predict the top n movies for each user.
## R
1. Data_Analysis: Interpretation and prediction of bush fires.
* data can be found in https://archive.ics.uci.edu/ml/machine-learning-databases/forest-fires/
* programming language: R 3.5.1
2. Visualization/shiny_app_usa_traffic: Shiny App using R for interactive visualization of traffic fatalities in the US - 2015
* Description of data sources:
  - Tabular data: 32K rows x 52 columns with spatial and temporal attributes. Data from: https://data.world/transportation/2015-traffic-fatalities
  - Tabular data in xls with SAT scores for each state in 56 rows and 19 columns. Data from: https://nces.ed.gov/programs/digest/d16/tables/dt16_226.40.asp

## EXTRA
An additional manual for setting up an Apache Spark cluster using 2 Ubuntu virtual machines is included in the file SettingUp_SparkCluster.pdf 
