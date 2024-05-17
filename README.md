# Google Play Store Analysis

## Overview:
This project is an analysis of the Google Play Store data, examining various aspects of app categories, ratings, reviews, and more.

## Problem Statement:
The objective of this analysis is to uncover insights and trends within the Google Play Store data, aiding app developers, marketers, and stakeholders in making data-driven decisions.

## Files:
- [apps.csv](https://github.com/seagle011/google-play-store-analysis/files/15348585/apps.csv): Contains all the details of the applications on Google Play. There are 13 features that describe a given app. The dataset includes the following columns:
  - `App`: Name of the app.
  - `Category`: Category to which the app belongs.
  - `Rating`: Average user rating of the app (out of 5).
  - `Reviews`: Number of user reviews for the app.
  - `Size`: Size of the app in megabytes (MB).
  - `Installs`: Number of installs of the app.
  - `Type`: Type of the app (e.g., Free, Paid).
  - `Price`: Price of the app 
(if applicable).
  - `Content Rating`: Content rating of the app (e.g., Everyone, Teen, Mature 17+, etc.).
  - `Genres`: Genres associated with the app.
  - `Last Updated`: Date when the app was last updated.
  - `Current Ver`: Current version of the app.
  - `Android Ver`: Minimum required Android version.

- [user_reviews.csv](https://github.com/seagle011/google-play-store-analysis/files/15348602/user_reviews.csv)
: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity. The dataset includes the following columns:
  - `App`: Name of the app.
  - `Review`: User review text.
  - `Sentiment`: Sentiment of the review (Positive, Negative, Neutral).
  - `Sentiment_Polarity`: Polarity score of the sentiment.
  - `Sentiment_Subjectivity`: Subjectivity score of the sentiment.


## Data Sources:
The datasets used in this analysis were obtained from [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps/data), and encompass information on app names, categories, ratings, prices, user reviews, and additional attributes.

## Tools and Libraries:
- Python
- pandas
- matplotlib
- seaborn
- plotly

## Analysis Steps:
1. Data Cleaning: Handling missing values, duplicates, etc.
2. Exploratory Data Analysis: Examining app categories, ratings, prices, etc.
3. Insights Derived: Identifying patterns, correlations, and notable findings from the data.

## Key Findings:
- The average volume of ratings across all app categories is 4.17. The histogram plot is skewed to the left indicating that the majority of the apps are highly rated with only a few exceptions in the low-rated apps.
- The majority of top rated apps (rating over 4) range from 2 MB to 20 MB.
- The vast majority of apps price themselves under $10.
- Paid apps have a relatively lower number of installs than free apps, though the difference is not as stark as one would expect.

## Visualizations:
- ![Average Rating](https://drive.google.com/file/d/1u2e3i2nSUITiT9zA95yZkUhbIk46kjbP/view?usp=sharing)
- ![Size vs Rating](https://drive.google.com/file/d/16n1veR6CawpIV5QABkJgwcv8ZqqucBi4/view?usp=sharing)
- ![Price vs Rating](https://drive.google.com/file/d/1-GIw25WI0O2Q3tTyrP-CBd1Tul572J2K/view?usp=sharing)
- ![Downloads of Paid vs Free](https://drive.google.com/file/d/1Ri9Wi9EuwVyOE7RkvLGSCOHyqw0qv85b/view?usp=sharing)

