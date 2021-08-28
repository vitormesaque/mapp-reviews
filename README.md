# Temporal dynamics of Requirements Engineering from mobile app reviews

MAPP-Reviews (Monitoring App Reviews) is a software, which (i) extracts requirements with negative evaluation from app reviews, (ii) generates time series based on the frequency of negative evaluation, and (iii) trains predictive models to identify requirements with higher trends of negative evaluation.

In MAPP-Reviews, we aim to detect the negative reviews of a software requirement that are starting to happen and make a forecast to see if they will become serious in the subsequent periods, i.e., high frequency in negative reviews. 

# Download app reviews

* [Download app reviews (Notebook)](https://github.com/vitormesaque/mapp-reviews/blob/d200f450d8939cbc86c0ec07f70cd83fb2671a2f/Mapp_Reviews_Web_Crawler.ipynb)

# Requirement Extraction
MAPP-Reviews uses the pre-trained RE-BERT model to extract software requirements from app reviews. RE-BERT uses a cross-domain training strategy, where the model was trained in 7 apps and tested in one unknown app for the test step.
* [Requirement Extraction (Notebook)](https://github.com/vitormesaque/mapp-reviews/blob/bbcb5b519f221b867202330b2d10dde197563b42/MAPP_Reviews_Requirement_Extraction_RE_BERT.ipynb)

# Requirement Clustering
MAPP-Reviews uses the k-means algorithm to obtain a clustering model of semantically similar software requirements.
* [Requirement Clustering (Notebook)](https://github.com/vitormesaque/mapp-reviews/blob/9813cbdf3e7358e6ed85d70b5d6d730cb1e8144f/Requirement_Clustering.ipynb)


# Requirements Time Series and Predictive Model
MAPP-Reviews uses the Prophet Forecasting Model. Prophet is a model from Facebook researchers for forecasting time series data considering non-linear trends at different time intervals, such as yearly, weekly, and daily seasonality.
* [Requiremenst Time Series and Predictive Model (Notebook)](https://github.com/vitormesaque/mapp-reviews/blob/bfcd5b5f19ea63c9d9670bbc2914c4eac3f28138/Time_Series_by_Week_and_App_Changepoints.ipynb)


# Related Repositories

* [RE-BERT](https://github.com/adailtonaraujo/RE-BERT)
* [Prophet](https://github.com/facebook/prophet)

