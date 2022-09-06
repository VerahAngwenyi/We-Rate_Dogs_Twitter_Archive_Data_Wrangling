# DAND Project 2; Data Wrangling
# Table Contents
1. Introduction
2. Gathering Data

  * Gathering Twitter enhanced archive csv

  * Gathering Image Predictions tsv

  * Gatherng JSON txt file using Twitter APIs

3. Assessing the Data

   * Visual Assessment

   * Progmatic Assessment

4. Cleaning the Data

5. Storing
6. Visualizations


# Introduction
This project, which is largely focused on wrangling data from the WeRateDogs Twitter account using Python and recording it in a Jupyter Notebook, was a component of the data wrangling phase of the Udacity Data Analyst Nanodegree program. This Twitter user ranks canines and provides amusing remarks. The numerators are typically bigger than the rating denominator of 10, which is typically 10. Since it contributes to the fun and popularity of WeRateDogs, this component was left in tact.

# Data Source
For this project, WeRateDogs offered their Twitter archive, which contained tweets up until August 1, 2017, along with the essential tweet data (tweet ID, date, content, etc.). The columns that were automatically retrieved from the "improved" csv file (twitter archive enhanced.csv) include the dog's name, the dog stages, the rating numerator, and the rating denominator (doggo, floofer, pupper, and puppo). Due to imperfect extraction, these columns required to be examined and cleaned. A link was provided for image_predictions.tsv which was downloaded programatically using the Requests library.

# Tools
Python | Numpy | Pandas | Matplotlib
requests| json | tweepy

# Conclusion
The project was very educative . I did learn the three steps that are involved in the data wrangling process. Vissual and programmatic assessment of a dataset were also well covered in this project.
