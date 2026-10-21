# streamgap-ai
# StreamGap AI
### Streaming Content Analytics & AI-Powered Title Similarity

## Overview
StreamGap AI is a data analytics and content-discovery project
built using a public Netflix Movies and TV Shows dataset.

The project combines an interactive Power BI report with a
content-based similarity engine that identifies titles with
similar descriptions and metadata.

## Problem Statement
Large streaming catalogues can be difficult to explore.
StreamGap analyses catalogue patterns and provides a simple
way to discover titles with similar content characteristics.

## Key Features
- Analyses Movies vs TV Shows.
- Explores content release-year trends.
- Identifies frequently listed genres.
- Compares catalogue representation by country.
- Recommends similar titles using text similarity.
- Provides an interactive demo using Gradio.

## Technologies Used
- Python
- pandas
- scikit-learn
- TF-IDF
- Cosine similarity
- Gradio
- Microsoft Power BI
- Power Query

## Dataset
Source: [Netflix Movies and TV Shows Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset includes titles, content types, countries, release
years, genres, and descriptions.

## How It Works
1. Load and clean the dataset.
2. Analyse catalogue patterns in Power BI.
3. Combine title descriptions and metadata into text features.
4. Convert text into numerical representations using TF-IDF.
5. Compare titles using cosine similarity.
6. Return similar titles through an interactive app.

## Limitations
- Recommendations are based on text similarity, not actual
  viewing histories or personal preferences.
- Similarity scores do not represent recommendation accuracy.
- Catalogue gaps do not necessarily indicate audience demand.

## Project Files
- `StreamGap_AI.ipynb` — Python notebook containing the
  data preparation and similarity engine.

## Author
Created as a portfolio project to practise data analytics,
data visualisation, and basic natural language processing.Netflix Content Analytics and AI-Powered Title Similarity
