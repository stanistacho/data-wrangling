# Project: Data wrangling & storing, analyzing, and visualizing  wrangled data
## by Stanislava Stachova
---

## Table of Contents
* Introduction
* Part I - Gathering data
* Part II - Assessing data
* Part III - Cleaning data
* Part IV - Analyse and Visualize data
* Conclusion
Data wrangling process is documented separately in **wrangle_report.pdf** Covering gather, assess, and clean part of the process. Storing, analyzing, and visualizing wrangled data is documented in **act_report.pdf**.
---

## Dataset
The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.
---


## Conclusion
1. Data wrangle process:

Within **Part I**, I have gathered three dataset files in a following way:
* I obtained WeRateDogs Twitter archive. As it was downloaded to pre-defined folder Downloads, I used shutil to move it programmaticaly to target folder.
* The tweet image predictions file (image_predictions.tsv) was hosted on Udacity's servers and was downloaded and saved programmatically.
* I was not able to obtain access to developer account, therefore I downloaded file tweet_json.txt manually and read it

In **Part II**, firstly, I have assessed all three datasets visually. Secondly, I used built in functions to assess tables programmatically.

The **Part III** deals with cleaning process. This part is divided to Qualitative issue cleaning and Tidiness issue cleaning. Issues were cleaned in line with standard cleaning process documentation and so Define, Code and Test. In this part I worked with the copies of read datasets.


2. Storying, analyzing and visualizing:
I have selected following items to either write or plot in non-formal style of blog article:
* dog stages
* features of popular dog stage using numerator, retweets and favorites
* favorite dog names
* from which devices the most data come from
---