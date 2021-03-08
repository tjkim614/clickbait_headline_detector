# clickbait_headline_detector

## Purpose
To detect clickbait articles based on headline using Natural Language Processing and various Machine Learning algorithms.

## Overview
- **Clickbaits** are internet links that entices users to follow its link to read, view, or listen to its contents, which are typically sensationalized or inaccurate information.
- Out of the five models that were implemented (Naive Bayes, Logistic Regression, Random Forests, KNN, SVM), SVM with word embeddings (SpaCy) performed the best, with a **92% F-1 score**.

## Process - OSEMN Model
![osemn](Images/new_osemn.png)

### Step 1: Obtain
Kaggle (32,000)
- clickbait headlines from ‘BuzzFeed’, ‘Upworthy’, ‘ViralNova’, ‘Thatscoop’, ‘Scoopwhoop’ and ‘ViralStories’ (16,000)
- non-clickbait headlines from ‘WikiNews’, ’New York Times’, ‘The Guardian’, and ‘The Hindu’ (16,000)
Webscraping from clickbait websites (16,707)
- clickhole.com (4,526)
- worldtruth.tv (12,181)
API's from major press companies (16,660)
- The New York Times (11,460)
- The Guardian (5,200)

Total of 65,367 headlines - 32,707 clickbait and 32,660 non-clickbait headlines

### Step 2: Scrub


### Step 3: Explore


### Step 4: Model


### Step 5: Interpret


## Conclusion and Future Works
- adfs
