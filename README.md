
## Exploratory Data Analysis and Regression Model on IMDB Movie Data

### What is Exploratory Data Analysis?
---------------------------------------
Exploratory Data Analysis (EDA) is a step in the Data Analysis Process, 
where a number of techniques are used to better understand a given dataset.

This involves but is not limited to:

* Identifying any outliers or missing values
* Identifying and extracting important variables
* Understanding the relationship(s) between variables
* Providing valuable insights relating to the data

### What is Linear Regression?
---------------------------------------
Linear Regression analysis is a powerful statistical process to help find the 
relationship between variables within a dataset, with the key focus being on relationships 
between the independent variables (predictors) and a dependent variable (outcome). 
It can be used to build models for inference or prediction. 

### Table of Contents
-----------------------
* Summary of my Project
* Required Libraries
* Data

### My Project
-----------------
In this [notebook](https://github.com/tadepoju/imdb-movie-regression/blob/Edit-data/IMDB%20Movie%20Analysis.ipynb) the data I used relates to IMDB Movie Data data to summarise the key characteristics of the dataset 
and to produce a regression model to predict the Gross for a film based on 
specific predictor variables.


Dataset is from [kaggle](https://www.kaggle.com/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)

|Variable | Description |
|:------- |:----------- |
|Poster_Link | Link of the poster that imdb using |
|Series_Title | Name of the movie |
|Released_Year | Year at which that movie released |
|Certificate | Certificate earned by that movie |
|Runtime | Total runtime of the movie |
|Genre | Genre of the movie |
|IMDB_Rating | Rating of the movie at IMDB site |
|Overview | Summary of movie |
|Meta_score | Score earned by the movie |
|Director | Name of the Director |
|Star1, Star2, Star3, Star4 | Name of the Stars in the movie |
|No_of_votes | Total number of votes |
|Gross | Money earned by that movie |

### Libraries
------------------------
In this notebook I have conducted my analysis using a few
popular **Python** libraries:
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Sklearn

### Data
----------
The dataset used can be found [here](https://github.com/tadepoju/imdb-movie-regression/blob/Edit-data/imdb_top_1000.csv)
 
