# Multilingual Movie Review Sentiment Analysis

## Overview

This project aims to analyze the sentiment of movie reviews in English, French, and Spanish. The dataset contains 30 movies (10 per language) with reviews and synopses stored in separate CSV files. The main steps are:

1. **Data Integration**: Combine data from `movie_reviews_eng.csv`, `movie_reviews_fr.csv`, and `movie_reviews_sp.csv` into a single Pandas DataFrame with columns for Title, Year, Synopsis, Review, and Original Language.

2. **Translation**: Convert French and Spanish text into English using HuggingFace's pre-trained transformers.

3. **Sentiment Analysis**: Employ HuggingFace's pre-trained transformers for sentiment analysis, appending results as a "Sentiment" column.

## Output

The project generates a CSV file with columns Title, Year, Synopsis, Review, Sentiment, and Original Language. The "Original Language" column shows the review's language pre-translation. The output DataFrame contains 30 rows, each representing a movie.

## Tools

- **Pandas**: Data manipulation and analysis.
- **HuggingFace Transformers**: Natural language processing for translation and sentiment analysis.
- **PyTorch**: Building and training machine learning models.

## Skills Gained

This project hones skills in:

- Data cleaning and manipulation with Pandas.
- Utilizing HuggingFace Transformers for translation and sentiment analysis.
- Creating and training models using PyTorch.
- Integrating diverse tools to solve complex problems in a unified workflow.

In essence, this project showcases the fusion of data manipulation, natural language processing, and machine learning to tackle various tasks within a diverse dataset.
