
# WeRateDogs Wrangle and Analyze Data

The dataset I wrangled (and analysed and visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

## Acknowledgements

 - [Udacity](https://udacity.com)
 - [@dog_rates](https://twitter.com/dog_rates)



## Tech Stack

**Python:** Pandas, Numpy, Seaborn, Matplotlib, requests,tweepy
## Documentation

**Project Details:**\
My tasks in this project are as follows:\
* Data wrangling, which consists of:
     * Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
    * Assessing data
    * Cleaning data
* Storing, analyzing, and visualizing your wrangled data
* Reporting on 1) my data wrangling efforts and 2) my data analyses and visualizations
**Gathering Data for this Project:**\
I gathered each of the three pieces of data as described below in a Jupyter Notebook titled wrangle_act.ipynb:
* The WeRateDogs Twitter archive. This is a file on hand. I downloaded this file manually by clicking the following link: twitter_archive_enhanced.csv
* The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and was downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
* Each tweet's retweet count and favorite ("like") count at minimum, and some additional data I found interesting. Using the tweet IDs in the WeRateDogs Twitter archive, I queried the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. 


## Methodology
After gathering each of the above pieces of data, I assessed them visually and programmatically for quality and tidiness issues. I detected and documented at least eight (8) quality issues and two (2) tidiness issues in the wrangle_act.ipynb Jupyter Notebook.\
**Cleaning Data for this Project:**\
I cleaned each of the issues I documented while assessing. Performed this cleaning in wrangle_act.ipynb as well. The result was a high quality and tidy master pandas DataFrame named twitter_archive_master.csv.\
**Storing, Analyzing, and Visualizing Data for this Project:**\
I analyzes and visualized the wrangled data in the wrangle_act.ipynb Jupyter Notebook. At least five (5) insights and six (6) visualizations was produced.
## Analysis Report
I created a written report called `wrangle_report.pdf` that briefly described my wrangling efforts.\
I also created a written report called `act_report.pdf` that communicated the insights and displayed the visualizations produced from the wrangled data.
## Screenshots
![Screenshot (90)](https://user-images.githubusercontent.com/58152694/143286139-3426687d-0983-40f5-ba0e-59364cd909bb.png)



## Feedback

If you have any feedback, please reach out to me at ayangidel@hotmail.com

