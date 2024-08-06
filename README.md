# StockPrediction

Project Overview

This repository houses a Python-based project focused on predicting stock prices by leveraging sentiment analysis on financial news headlines. News articles are scraped from Finviz using BeautifulSoup, and sentiment is determined using the FinBERT model from Hugging Face. Data visualization and exploration are facilitated by Matplotlib, Seaborn, and Weights & Biases (Wandb).

Key Features

1.News Data Acquisition: Efficiently scrapes financial news headlines from Finviz using BeautifulSoup.
2.Sentiment Analysis: Employs the powerful FinBERT model to accurately classify news sentiment. 
3.Data Visualization: Provides insightful visualizations using Matplotlib, Seaborn, and Wandb for comprehensive analysis.
4.Time Series Analysis: Explores stock price trends and their correlation with news sentiment over time.

Technologies Used

1.Python 
2.BeautifulSoup4
3.Numpy 
4.Pandas
5.Matplotlib 
6.Seaborn 
7.Wandb 
8.Hugging Face Transformers 
9.FinBERT model

Project Structure

1.data: Stores scraped news data and processed datasets. 
2.notebooks: Contains Jupyter notebooks for data exploration, model training, and visualization. 
3.src: Houses Python scripts for data preprocessing, model building, and evaluation.
4.models: Saves trained models.

Getting Started

1.Clone this repository. 
2.Install required dependencies using pip install -r requirements.txt.
3.Collect your Finviz API key and other necessary credentials. 
4.Run the Jupyter notebooks or Python scripts to execute the project.
