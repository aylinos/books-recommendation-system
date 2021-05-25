# Books Recommendation System
Data Science project in semester 4. Finished development on 10 May 2021. Individual Work

### Goal:
Introduction to working extensively with the IBM Foundational Methodology for Data Science
<br/> <br/>

**Python version:** 3.9.1 <br/>
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, surprise, fuzzywuzzy, selenium, bs4 <br/>
**Data source:** [Kaggle](https://www.kaggle.com/ruchi798/bookcrossing-dataset) <br/> <br/>

### Project idea: 
Helping individuals with choosing suitable books for their taste by developing a recommender system that:
➔ Suggests similar books
➔ Predicts book rating per user
➔ Recommends books based on personal taste.


# Key implementations
* Data cleaning
* Data enrichment
* Web scraping
* Exploratory Data Analysis (EDA)
* Statistics
* Modeling 
* Evaluation

Detailed explanation on all data manipulations and processes is available in each notebook.


## EDA:
* Merge datasets
* Split / Drop columns
* Handle NaN & irrelevant values
* Change data types
* String & number validation using REGEX
* Observe data quality
* Analyse data
* Plot data 
* Suggest directions for modeling


## Data Preparation:
* Dive more into data quality issues & handle those (eg: Inputs of 0 for book rating | Variations in isbn number for the same book title)
* Web scrape publicly available book information from [Goodreads.com](goodreads.com) & [Amazon.com](amazon.com)
* Extract new columns from the dataset (eg: Average book rating | Total count of raters per book)

## Statistics
Offer generalized recommendations to each user, based on popularity and high rating | Weighted Rating (WR) formula

## Modeling
**Metadata-based filtering:** Suggest similar items to a particular item based on the metadata <br/>
CountVectorizer | Cosine Similarity 
<br/>
**Collaborative filtering:** Predict book rating per user <br/>
Singular Value Decomposition (SVD) model | Train & Test sets | MSE | RMSE / NRMSE | Cross validation

