# Testing Project

This is a sample project downloaded from Kaggle, which contains the data set and a rmd file. Feel free to make any commits and branchs to test all of the git functions. 

## Modification on this project
If you want to make change to this project, there are just two steps you need to do,

1. Clone repository via GitHub Desktop

    _You can find the clone repository under file tab of GitHub desktop, choose Credigy/Test1. You can change the default locol path if you want._


2. Make any change you want to by modifying the code under master branch or creating your own branch. 

__Please let me know if you have any questions.__


_*Below is the project and data description._

## Project info
### Context
While many public datasets (on Kaggle and the like) provide Apple App Store data, there are not many counterpart datasets available for Google Play Store apps anywhere on the web. On digging deeper, I found out that iTunes App Store page deploys a nicely indexed appendix-like structure to allow for simple and easy web scraping. On the other hand, Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

### Content
Each app (row) has values for catergory, rating, size, and more.

### Acknowledgements
This information is scraped from the Google Play Store. This app information would not be available without it.

### Inspiration
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market!

## Data set structure:
* 'googleplaystore.csv' : This file contains all the details of the applications on Google Play. There are 13 features that describe a given app.
    - App: Application name
    - Category: Category the app belongs to ss
    - Rating: Overall user rating of the app (as when scraped)
    - Reviews: Number of user reviews for the app (as when scraped)
    - Size: Size of the app (as when scraped)
    - Installs: Number of user downloads/installs for the app (as when scraped)
    - Type: Paid or Free
    - Price: Price of the app (as when scraped)
    - Content Rating: Age group the app is targeted at - Children / Mature 21+ / Adult
    - Genres: An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
    - Last Updated: Date when the app was last updated on Play Store (as when scraped)
    - Current Ver: Current version of the app available on Play Store (as when scraped)
    - Android Ver: Min required Android version (as when scraped)

* 'googleplaystore_user_reviews.csv' : This file contains the first 'most relevant' 100 reviews for each app. Each review text/comment has been pre-processed and attributed with 3 new features - Sentiment, Sentiment Polarity and Sentiment Subjectivity.
    - App: Name of app
    - Translated_Review: User review (Preprocessed and translated to English)
    - Sentiment: Positive/Negative/Neutral (Preprocessed)
    - Sentiment_Polarity: Sentiment polarity score
    - Sentiment_Subjectivity: Sentiment subjectivity score

## Code 
The R Markdown code is about a EDA on the data set. It contains a lots of beautiful and interesting plots. 


__You can find the original link below:__

_[Kaggle Porject and Data: Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps/home)_

_[Kaggle Kernels: Google Play Store EDA (plotting with Highcharts)
](https://www.kaggle.com/danilodiogo/google-play-store-eda-plotting-with-highcharts)_





