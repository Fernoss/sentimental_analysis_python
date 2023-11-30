# Sentimental News Analysis 📰🐍

Welcome to Sentimental News Analysis, a Python project that harnesses the power of newsdata.io API and TextBlob library for sentiment analysis on news articles. Dive into the emotional tones of news coverage and gain insights into articles related to specific keywords.

## Overview

This project allows you to perform sentimental analysis on news articles, breaking them down into positive, neutral, and negative sentiments. By utilizing newsdata.io API, you can fetch articles based on keywords and country, providing a comprehensive view of sentiments around specific topics.

## How it Works

1. **API Authorization:** Initialize the NewsDataApiClient with your API key for access to newsdata.io.

2. **Fetching News Articles:** Utilize the News API to retrieve news articles based on specific keywords and country.

3. **Sentiment Analysis:** Use TextBlob library to analyze the sentiment of the articles' descriptions. The sentiment scores are categorized as positive, neutral, or negative.

4. **Visualization:** Visualize the sentiment scores through histograms and pie charts, offering an intuitive understanding of the emotional tones in the news coverage.

## Usage

To use this project:

1. Obtain your API key from newsdata.io and update the `API_KEY` variable in the `config.py` file.

2. Run the provided Python script to fetch news articles, perform sentiment analysis, and visualize the results.

3. Explore the sentiment scores for each article and gain insights into the emotional context of news coverage.

## Dependencies

- [TextBlob](https://textblob.readthedocs.io/)
- [NewsDataApiClient](https://github.com/newsdataapi/python-newsdataapi)
- [Matplotlib](https://matplotlib.org/)

Feel free to explore, analyze, and understand the sentiments surrounding different topics in the news!
