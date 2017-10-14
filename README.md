# Election-Vote-Share-Prediction
Analyzed and Raw dataset to our paper:

"Election Vote Share Prediction using a Sentiment-based Fusion of Twitter Data with Google Trends and Online Polls"

## Description:
This dataset contains more than 370,000 tweets containing the keywords "Trump" and/or "Clinton", gathered from January 2016 to January 2017.
Raw tweets are available as well as a refined dataset (removed punctuations), which contains the output of 2 different sentiment analysis algorithms for each tweet.
The dataset was used to predict the popular vote share of US2016 Election, with mean error rate of less than 2%.

## To use the dataset:

Raw Tweets about each candidate can be found in the branch with their name.
Each Zip file in those branches contains a couple of csv files of the following format:

          username;date;retweets;favorites;text;geo;mentions;hashtags;id;permalink

The .rds files in the main branch include our own refined and augmented dataset, the can be opened if you have R installed on your device.
We suggest Rstudio as a nice platform to view and alter rds files.


## Copyright:

Please note that this dataset is created for “Election Vote Share Prediction Using a Sentiment-Based Fusion of Twitter Data with Google Trends and Online Polls” presented at KDCloudApps2017 at 6th international conference on Data Science, Technology and Applications (DATA 2017). When using the dataset you are obliged to cite the paper at:

Kassraie, P.1, Modirshanechi, A.1, & Aghajan, H. (2017). Election Vote Share Prediction using a Sentiment-based Fusion of Twitter Data with Google Trends and Online Polls. In Data 2017, KDCloudApps. Madrid, Spain: INSTICC.
DOI: 10.5220/0006484303630370 (1 First Two Authors Contributed Equally)


## Further Information:

You can contact the owners if you had any questions regarding the dataset or the paper at:

Parnian Kassraie, kasraei_parnian@ee.sharif.ir

Alireza Modirshanechi, modir_alireza@ee.sharif.ir
