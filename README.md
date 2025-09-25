## Sentiment Analysis on Google Play Store App

### Introduction

This repository contains three Jupyter notebooks for Analysis and Sentiment Analysis of Google Play Store Apps. 

### Overview
**Part 1: Exploration**
* Analyze and prepare the dataset for later processing
* Derive first insights from it including visualizations

**Part 2: Sentiment Analysis**
* Analyze the distribution of sentiments in the reviews dataset
* Compare LLM-based sentiment analysis on a random sample of this dataset with at least one specialized
sentiment analysis model and comment on your findings.

**Part 3: Insights and Recommendations**
* Derive further insights about user opinions on the apps combining both tables using an LLM-based
approach
* Generate a small synthetic dataset of users (10+) and their installed apps (60-100 apps per user)
* Propose replacement options for apps with bad ratings for each user leveraging Naive, Sentence Transformer and LLM based approaches
  
### Installation and Usage

1. Clone the repository: `git clone git@github.com:gaurav00700/SentimentAnalysis_GooglePlayStoreApps.git`
2. Navigate to the project directory: `cd SentimentAnalysis_GooglePlayStoreApps`
3. Create and activate virtual environment: `
conda create -n venv python=3.10 && conda activate venv`
3. Install necessary python packages: `pip install -r requirements.txt`

### Project Structure

```
├── SentimentAnalysis_GooglePlayStoreApps
│  ├── data
│  │   ├── input
│  │   │   ├── googleplaystore_user_reviews.csv
│  │   │   ├── googleplaystore.csv
|  ├── part1_exploration_googleplay.ipynb 
|  ├── part2_sentiment_analysis_googleplay.ipynb
|  ├── part3_insights_recommendations_googleplay.ipynb
|  ├── requirements.txt
```
