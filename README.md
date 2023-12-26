# Meal_Logging_Behaviour_Insights

This repository contains a Python script for analyzing user meal logging behavior.

### 1. Data Loading and Preprocessing
- Loads meal logging data from a JSON file.
- Converts timestamps to datetime format and extracts date, time, hour, and month information.
- Preprocesses descriptions by removing stopwords
- Visualizes word clouds for all words and food-related words.

### 2. Sentiment Analysis
- Conducts sentiment analysis on meal descriptions
- Ranks meal entries based on sentiment scores

### 3. Behavioral Analysis
- Categorizes meal entries into breakfast, lunch, or dinner based on log times.
- Calculates monthly average mood scores for each user and visualizes them in monthly graphs.
- Identifies users' favorite meal types based on sentiment scores.

### 4. User Activity Analysis
- Visualizes monthly user activity based on the number of actions (logs) for each user in bar charts.

## File Structure
- `data.json`: Input dataset containing meal logging information.
- `Meal_Logging_Behaviour_Insights.ipynb`: Jupyter Notebook containing the Python script.

## Libraries Used
- pandas, matplotlib, nltk, wordcloud
