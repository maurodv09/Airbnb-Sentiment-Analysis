# Airbnb-Sentiment-Analysis
This project aims to analyze the sentiment of Airbnb reviews in New York City for the year 2023. 

The goal is to understand the overall sentiment of guests’ experiences and identify common themes in positive and negative feedback. The insights gained from this analysis are expected to help Airbnb hosts make more informed decision and enable the platform itself to improve the overall guest experience by addressing common issues and enhancing positive aspects.

For that purpose, the project is divided into two Notebooks:
- [Data Cleaning](https://github.com/maurodv09/Airbnb-Sentiment-Analysis/blob/main/data_cleaning.ipynb): Standard dataset cleaning, as well as Text Cleaning for each review.
- [Sentiment Analysis](https://github.com/maurodv09/Airbnb-Sentiment-Analysis/blob/main/sentiment_analysis.ipynb): Classification, Visualization and Conclusions.


## Dataset
The data was obteinded from [Inside Airbnb](https://insideairbnb.com/get-the-data/). The file is called *reviews.csv* in the New York City section and it contains the reviews of multiple years. The specific data for 2023 was extracted in the *Data Cleaning Notebook*.

The results of the reviews analyzed were stored in the analysis_data folder


## Limitations
Please note that only English-written reviews will be analyzed, which may introduce a bias towards English-speaking individuals


## Tools
- python3
- jupyter Notebook
