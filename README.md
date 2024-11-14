![Distribution of average ratings by genre](https://github.com/user-attachments/assets/369ac8bf-994f-40f3-8cf2-7e868ee1d29a)# GROUP-7-PROJECT

## PHASE 2: Final Project Submission

Please fill out:
* Students name: 
	1. **Vivian Muiruri** (vivian.muiruri@student.moringaschool.com) 

	2. **Calvin Angoye** (calvin.angoye@student.moringaschool.com)

	3. Dominic Oseko (dominic.oseko@student.moringaschool.com)

	4. Soudie Okwaro (soudie.okwaro@student.moringaschool.com)

	5. Winfred Karimi(winfred.karimi@student.moringaschool.com)

	6. 

	7. 


* Student pace: self paced / part time / full time; **PART TIME**
* Scheduled project review date/time: **FRIDAY, 11th 2024**
* Instructor name: SAMUEL KARU
* Blog post URL: https://github.com/MuiruriVivian/PHASE-2-GROUP-7-PROJECT

## Business Problem

Your company now sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of your company's new movie studio can use to help decide what type of films to create.

## The Data Source

> IMDB (https://www.imdb.com/)

> bom.movie_gross.csv.gz

> tn.movie_budgets.csv.gz

> tmdb.movies.csv.gz

The files are in different formats that is, CSV and TSV files and can be opened using the pd.read_csv.
Data from IMDB is in a SQLite Database. We combined 

> tmdb.movies.csv.gz and IMDB (https://www.imdb.com/) to form **cleaned merged_data.csv** 

and 

> bom.movie_gross.csv.gz and tn.movie_budgets.csv.gz to form **cleaned gross_budget.csv**


## Importing the Libraries

The following libraries were imported for data analysis and visualization tasks:

* numpy for high level mathematical functions, working with Arrays and performing statistical calculations **import numpy as np** 

* pandas data manipulation, reading, analysis and managing data structure for tablular data **import pandas as pd**  

* seaborn and matplotlib for data visualization such as bar charts, line plots, and scatter plots **import seaborn as sns** and  **import matplotlib.pyplot as plt %matplotlib inline** 

* matplotlib image for image upload as **import matplotlib.image as mpimg**

* Sqlite3 in Python for loading the SQLite library, which provides a lightweight, disk-based database system as **import sqlite3**

* Scikit-Learn library  for classification, regression, clustering, and dimensionality reduction, along with utilities for preprocessing, model selection, and evaluation as **import sklearn as sk**

* Statsmodels library, a robust statistical package that is widely used for conducting statistical tests, modeling, and data exploration as **import statsmodels.api as sm**

* Stats module from SciPy to provides a vast range of statistical tools, including probability distributions, statistical tests, and functions for descriptive statistics, for data analysis and hypothesis testing as **import scipy.stats as stats**


## Data Cleaning 
The four dataset will go through sanity check first thats is data cleaning, it includes:
*  Converting some columns that are are supposed to be numerical i.e production_budget, domestic_gross_y, worldwide_gross from object dtype to float dtype

*  Splitting the genre column to make it easier to analyze each genre independently.

*  Check the null or missing values and fill them, and drop where need be

* Check and drop duplicates
  
* Check and drop outliers


## Objectives 

* Identify Popular Film Genres by popularity

* Identify which type of film are profitable

* Identify Emerging Trends and Audience Preferences

* identify months with highest profit

## Data Analysis 

Our Data analysis structure includes:

* Introduction

* Exploratory Data Analysis (EDA)

* Statistical Distribution

* Inferential Statistics

* Conclusion

* Recommendation



## Visualizations
![Uploading Distribution of average ratings by genre.png…]()





## Findings


## Conclusion 


## Recommendation  
    






