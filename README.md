# A closer look into the data of Seattle’s Airbnb market


### Table of Contents

1. [The Libraries That I Have Used](#libraries)
2. [My Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Summary Of The Results](#results)
5. [Acknowledgements](#acknowledgements)

## The Libraries That I Have Used <a name="libraries"></a>

The Anaconda Python 3.0 distribution was used to accomplish the project. In addition, the following python libraries have been implemented: 

1. Collections
2. Matplotlib 
3. NLTK
4. NumPy
5. Pandas
6. Seaborn
7. Sklearn

## My Project Motivation<a name="motivation"></a>

I was curious to look into the AirBnB dataset for Seattle. I needed to discover more about pricing patterns, customer feedback, and pricing forecasting. Some of the questions I've looked into are: 

# Pricing Trends

1. What is the peak season in Seattle and how does pricing change with the seasons?
2. How does pricing differ by neighbourhood, and which Seattle neighbourhoods are the most expensive?
3. What effect does the kind of property in an area have on the price of the most costly neighbourhoods and the most prevalent property types? 

# Sentiment Analysis of Reviews

4. How can we classify reviews focused on sentiments?
5. Can we correlate positive and negative attitudes from reviews to neighbourhoods to see which neighbourhoods have higher positive sentiments and which have higher negative sentiments?
6. Is it possible to look into some of the worst reviews for additional insights?

# Price Prediction
7. Can we forecast a listing's price? What aspects of the listing have the best correlation with price prediction?


## File Descriptions <a name="files"></a>

The analysis performed in order to investigate the dataset, data preparation and wrangling, and the creation of prediction models in order to answer the questions above are all documented in the Jupyter notebook. Markdown cells are included in the notebook to aid in the documentation of the procedures as well as the communication of findings based on each analysis. 

For reference an HTML version of the notebook is also available.

Lastly, the seattle folder contains the dataset from Kaggle (https://www.kaggle.com/airbnb/seattle).
Finally, the dataset from Kaggle(https://www.kaggle.com/airbnb/seattle) is contained in the seattle folder.
 
It consists of three files: 
- calendar.csv: calendar attainability of listings and price
- listings.csv: detail about all the attainability listings
- reviews.csv: listing customer feedback

## Summary Of The Results<a name="results"></a>

The following are among the most major findings from the analysis:

1. The summer months of June through August are considered to be the high season in Seattle, with July being the absolute peak. 
2. The most expensive neighbourhood in Seattle was "Southeast Magnolia," followed by Portage Bay. The best price was Rainier Beach.
3. When I looked into other neighbourhoods and property types, I discovered that the most costly houses are in Portage Bay, followed by residences in West Queen Anne and Westlake. 
4. I was able to map the reviews to their various sentiments of positive, negative, or neutral using Sentiment Intensity Analyzer. I discovered that 97.2 percent of reviews were generally good, with only 1% being negative and 1.8 percent being neutral.
5. By looking at review feelings by neighbourhood, I discovered that Roxhill, Cedar Park, and Pinehurst had the most positive ratings, while University District, Holly Park, and View Ridge had the least.
6. Sentiment Intensity Analyzer combines non-English reviews with negative sentiments, which I discovered while investigating the worst reviews. 
7. I was capable of predicting price based on a prepared and cleaned dataset using Linear Regression, with a r2score of 0.62 on both the training and test datasets.
8. It was discovered that a combination of host characteristics and descriptive information about the listing had the greatest effect on the price.

Blog on Airbnb-Seattle-udacity-project

I have written a blog on website Github Page about the project and observations. Link is down below https://abdishakury.github.io/


## Acknowledgements<a name="acknowledgements"></a>

Kudos to AirBnB for uploading the dataset and Kaggle for hosting it; the dataset can be found here: https://www.kaggle.com/airbnb/seattle

SentimentIntensity Analyzer Reference: https://www.nltk.org/api/nltk.sentiment.html

Heatmap Reference: https://seaborn.pydata.org/generated/seaborn.heatmap.html

