# Wrangle-and-Analyze-Data
The 5th project of Udacity Data Analyst Nanodegree



# Introduction:
Real-world data rarely comes clean. Using Python and its libraries, I will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. I will document my wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

(dog pic.png)

# What Software Do I Need?
I used Jupyter Notebook for this project. The following packages (libraries) are the most important libraries used in this project:

* pandas
* NumPy
* requests
* tweepy
* json

# Project Details
The tasks in this project are as follows:

Data wrangling, which consists of:

* Gathering data
* Assessing data
* Cleaning data
* Storing, analyzing, and visualizing the wrangled data
* Reporting for:
  * Data wrangling efforts
  * Data analyses and visualizations


# Project Workspace page:
* wrangle_act.ipynb: code for gathering, assessing, cleaning, analyzing, and visualizing data
* wrangle_report.pdf: documentation for data wrangling steps: gather, assess, and clean
* act_report.pdf: documentation of analysis and insights into final data
* twitter_archive_enhanced.csv: file as given
* image_predictions.tsv: file downloaded programmatically
* tweet_json.txt: file constructed via API
* twitter_archive_master.csv: combined and cleaned data
