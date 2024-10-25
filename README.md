# WeRateDogs Data Wrangling Project

## Project Details

This project was completed as part of the Udacity Data Analyst Nanodegree program. The main objective of this project was to gather, assess, and clean data from multiple sources related to the WeRateDogs Twitter account. The analysis involved data wrangling steps including data collection, cleaning, and storing data for later analysis.

The final cleaned dataset was used to derive insights about the WeRateDogs Twitter activity, including popular dog ratings and other interesting trends. Visualizations were used to present these insights effectively, and the project emphasizes the importance of proper data wrangling techniques for accurate analysis.

## Dataset

The dataset used in this project comes from multiple sources:

- **Twitter Archive**: The main dataset was provided by WeRateDogs, containing the original tweets and associated metadata.
- **Image Predictions File**: Generated by a neural network that predicts the breed of the dog in each photo.
- **Twitter API Data**: Additional data, such as retweet count and favorite count, were gathered using the Twitter API.

The project involved gathering the data from these sources, assessing their quality and tidiness issues, and cleaning them to create a final master dataset ready for analysis.

## Summary of Findings

After analyzing the data, several interesting insights were observed:

- The highest-rated dogs on WeRateDogs often feature exaggerated and amusing ratings, with 12/10 and 13/10 being very common scores.
- Dog breeds predicted to be more friendly and popular, such as Golden Retrievers and Labrador Retrievers, were more likely to receive higher ratings.
- Tweets with photos tended to get more engagement (favorites and retweets) compared to tweets without photos.

These findings were presented through various visualizations that illustrated trends in rating distribution, breed popularity, and user engagement.

## Key Insights for Presentation

The presentation focused on the storytelling aspects of the data. Visualizations were selected to highlight key trends, such as the distribution of dog ratings, and the relationship between predicted dog breed and tweet engagement metrics like favorite and retweet counts. The goal was to make the insights accessible and engaging for the audience, showcasing how different breeds and dog ratings impact social media success on WeRateDogs.

## Files

- `wrangle_act.ipynb`: Jupyter Notebook containing the entire data wrangling process, including gathering, assessing, cleaning, and analyzing the data.
- `twitter_archive_master.csv`: The cleaned dataset used for analysis.
- `WeRateDogs_Wrangling_Report.pdf`: A detailed report on the data wrangling process, documenting quality and tidiness issues and how they were resolved.
- `WeRateDogs_Insights_Presentation.pdf`: A presentation summarizing the key findings and insights from the analysis.

## How to Use

To explore this project, clone the repository and open the Jupyter Notebook (`wrangle_act.ipynb`) to see the complete data wrangling process. The cleaned dataset (`twitter_archive_master.csv`) can be used to reproduce the analysis or conduct further research.

## Requirements

The following Python libraries were used in this project:

- `pandas`
- `numpy`
- `requests`
- `tweepy`
- `json`
- `matplotlib`

To install the required libraries, run:

```sh
pip install -r requirements.txt
