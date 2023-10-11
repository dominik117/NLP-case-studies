# Movie Similarity Analysis Using Word Embeddings

In this project, we dive deep into a dataset containing over 4000 short movie plot descriptions. Our aim is to find similarities between these movies based on their descriptions using cosine similarities and word embeddings.

## Table of Contents
- [Introduction](#introduction)
- [Background](#background)
- [Data Collection](#data-collection)
- [Data Cleaning and Pre-processing](#data-cleaning-and-pre-processing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Methodology](#methodology)
- [Results](#results)
- [Discussion](#discussion)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

## Introduction
We aim to uncover relationships between movies by analyzing the textual content of their plot descriptions. This is beneficial for content recommendation, categorization, and understanding narrative trends.

## Background
With the proliferation of streaming services and movies, there's a growing need to effectively categorize, recommend, and understand the vast amounts of content available to viewers. Textual descriptions, like movie plots, are a rich source of data for this kind of analysis.

## Data Collection
- **Source**: 
- **Size**: Over 4000 short movie plot descriptions.

## Data Cleaning and Pre-processing
Initial data processing steps included:
- Removing duplicates
- Handling missing descriptions
- Standardizing text (e.g., lowercasing, removing special characters)

## Exploratory Data Analysis (EDA)
We conducted a preliminary examination of the data to:
- Understand the distribution of movie genres.
- Identify common words and phrases across descriptions.
- Visualize word frequencies.

## Methodology
1. **Word Embeddings**: We used "Word2Vec" and "FastText" to convert movie plot descriptions into vectors.
2. **Cosine Similarity**: Using the embeddings, we computed the cosine similarity between movie descriptions to identify movies with similar content.

## Results
Our analysis was able to group movies based on narrative similarities. For instance, movies in the "romantic" genre were often clustered together, indicating shared narrative elements.

## Discussion
The effectiveness of the model in clustering similar movies showcases the power of word embeddings in textual content analysis. One limitation observed was _. Limitations observed were also _.

## Conclusion
Word embeddings, combined with cosine similarity, offer a robust method for analyzing and finding similarities in textual data like movie plot descriptions.

## Recommendations
1. Streaming platforms can use this approach for building recommendation engines.
2. Production companies can analyze narrative trends and audience preferences.
3. Further refinement can be done by incorporating more metadata like cast, director, and production year.


