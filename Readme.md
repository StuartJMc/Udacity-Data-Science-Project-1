# Data Science Project 1: Writing a Data Science Blog Post

Repo Contents

- data/airbnb : seattle airbnb open data -> https://www.kaggle.com/airbnb/seattle/data
- project-1-explore: notebook, following CRISP-DM framework, that outlines buisness questions related to the data before processing & analysing the data to gain insights


## Project Context

Airbnb is an online home/vacation rental marketplace founded in 2007. The platform allows users to list their home/space for rent, in return for a comission for each booking. The site allows users to customize their listing (or page) to attract potential guests, and set the price of renting the property. As well as renters/ tourists to lieve reviews about their experience. This data, along with other metrics, is available for listings in the seattle area through **Seattle Airbnb Open Data** avaiable on kaggle. The dataset contains:

- **calendar** data: availability & pricing on 3818 listings from 2016-01-04 to 2017-01-02
- **listings** data: Attributes scraped from the web pages of the 3818 listings, all scraped on 2016-01-04
- **reviews** data: Reviews left by users for 3191 listings from 2009-06-07 to 2016-01-03

With knowledge of the available data, the following business questions could be posed:

1. Does increased availability reflect in worse reviews? 
- (To determine if properties left avaiable for longer suffer from worse reviews)
2. Does length of listing description have an affect on property ratings? 
- (To determine if more detailed descriptions reflects an overall "better" experience for the renter)
3. Does listing price vary seasonally?
- (To determine if owners need to adjust their prices periodically)
4. How does the size of a property relate to price?
- (To determine if owners can estimate their pricing based on the space available)
5. Is price depenednt on location?
- (To determine if owners can estimate their pricing based on their location)

Further more, answers to these questions could determine useful features for building a model to predict listing price, based on a propertie's attributes. This would help users determine if they are over/under pricing their properties.

## Process

All analysis/insights is performed in the project-1-explore notebook. A summary of the context is as follows:

1. Business Understanding
2. Data Assessment
- The three data sourced are assessed for suitability, and any required cleaning is noted
3. Prepare Data
- Using the outcome of the assessment, each data set is prepared/cleaned so that analysis can be performed
4. Data Modelling & Evaluation
- All listed buisness questions are answered through anlysis/ modelling of the data
