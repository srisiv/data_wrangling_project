# Data Wrangling Project


## Dataset

> There were 3 data files provided as part of this project.  
- twitter-archive-enhanced.csv:  this file is a curated dataset from Udacity from the WeRateDogs twitter archive. It contained fields like the twitter text and had the dog ratings and catgory extracted from the description. The data from this file was to be cleaned.
- image-predictions.tsv: This file was a predictions file that contained predictions of the type of animal in the image files uploaded with with a tweet.
- tweet_json.txt is the WeRateDogs twitter archive downloaded using the twitter API and is used to extract the retweet count and like count to supplement what was already present in twitter-archive-enhanced.csv
- twitter_archive_master.csv is the file with data that is consolidated from the above 3 data files and cleaned by wrangle_act.ipynb.


## Summary of Findings

> The analysis is in the following files
- wrangle_act.ipynb: This file implements the required data cleaning and consolidation of the data extracted from the above mentioned data files and generates a new master file twitter_archive_master.csv that is used for further analysis.
- wrangle_report.pdf: This report summarizes the data cleaning methods used in wrangle_act.ipynb
- act_report.pdf: Contains analysis and insights done from the cleaned and consolidated twitter_archive_master.csv dataset.
