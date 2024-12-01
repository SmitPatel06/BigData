<b>Twitter Big Data Analysis Project</b>

<b>Overview</b>
  
This project demonstrates the analysis of a large-scale Twitter dataset using Apache Spark. The main goal is to process, clean, and analyze the data to extract meaningful insights such as tweet trends, sentiment distribution, and word frequencies. The project also includes a machine learning pipeline to perform sentiment analysis using logistic regression.

<b>Features</b>

•	Big Data Handling: Efficiently processes large datasets using PySpark.

•	Data Cleaning and Preparation: Cleans and preprocesses raw Twitter data.

•	Time-Series Analysis: Visualizes tweet volume trends over time.

•	Sentiment Analysis: Analyzes and visualizes sentiment distribution across tweets.

•	Natural Language Processing (NLP): Tokenizes tweets, removes stopwords, and identifies word frequencies.

•	Machine Learning: Builds a sentiment prediction model using logistic regression.

<b>Technologies Used</b>

•	Apache Spark: For distributed data processing.

•	PySpark MLlib: For machine learning and feature engineering.

•	Matplotlib: For visualizing trends and insights.

•	Python: Primary programming language for implementation.

<b>Project Workflow</b>

  1.	Set Up Spark Session
    o	Configured with memory allocation and legacy time parser policy for efficient big data handling.
  2.	Load and Preprocess Data
    o	Loads a CSV dataset containing tweets.
    o	Renames columns and selects relevant fields for analysis.
    o	Converts timestamps to a consistent format and handles missing values.
  3.	Data Analysis
    o	Analyz tweet volume over time and visualizes it.
    o	Groups and visualizes sentiment distribution (positive vs. negative).
  4.	NLP and Word Frequency Analysis
    o	Tokenizes tweet text into individual words.
    o	Removes stopwords to focus on meaningful terms.
    o	Counts and visualizes the most frequent words in tweets.
  5.	Machine Learning Pipeline
    o	Builds a pipeline with tokenization, stopword removal, feature vectorization, and logistic regression.
    o	Trains and evaluates a sentiment analysis model.

<b>Installation</b>
1.	Install Python (version 3.8 or higher recommended).
2.	Install required libraries:

Usage
1.	Run the notebook file (Project.ipynb) using Jupyter Notebook or Google Colab.
2.	The script processes the dataset and generates visualizations for trends, sentiment, and word frequencies.
3.	View model predictions for sentiment classification.

Example Visualizations
1.	Tweet Volume Over Time: Shows trends in tweet activity across timestamps.
2.	Sentiment Distribution: Bar chart displaying positive and negative sentiment counts.
3.	Top Words: Highlights the most frequently used words in tweets.

Dataset
  •	The dataset used contains:
    o	Sentiment labels (0 for Negative, 4 for Positive).
    o	User metadata and original tweet content.
  
  •	File: Twitter_Dataset.csv.

Contribution
Feel free to fork this repository and contribute. Submit pull requests for any improvements or new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.

