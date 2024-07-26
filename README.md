# Squid-Game-Sentiment-Analysis

This repository contains a Jupyter Notebook that performs sentiment analysis on Twitter data related to the Netflix series "Squid Game." The analysis includes data preprocessing, sentiment classification, and visualization of the results.

## Overview

The project aims to analyze the sentiment of tweets about "Squid Game" using natural language processing (NLP) techniques. The sentiment analysis helps understand the public's perception of the series.

## Dataset

The dataset used for this analysis is a collection of tweets related to "Squid Game." It includes columns such as `text` (tweet content), `date`, and other metadata. The dataset was preprocessed to remove irrelevant columns and handle missing values.

## Methodology

1. **Data Cleaning:** 
   - Removal of unnecessary columns and handling missing data.
   - Text preprocessing, including converting text to lowercase, removing URLs, HTML tags, punctuation, and stopwords, and stemming words.

2. **Visualization:**
   - Word cloud visualization to identify common words in the tweets.

3. **Sentiment Classification:**
   - The notebook utilizes a machine learning model to classify the sentiment of tweets as positive, negative, or neutral.

## Tools and Libraries

The analysis was conducted using the following tools and libraries:
- Python
- Pandas
- NumPy
- Matplotlib
- WordCloud
- NLTK (Natural Language Toolkit)

## Results

The analysis provides insights into the general sentiment around "Squid Game," highlighting the most common positive and negative opinions expressed by viewers on Twitter.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements or additions to the analysis.
