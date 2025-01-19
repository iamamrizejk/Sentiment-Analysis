# Sentiment Analysis 🙂🙃

**Sentiment Analysis for YouTube, Reddit, and Reviews** is a machine learning-based project that analyzes and classifies the sentiment of comments from **YouTube videos**, **Reddit posts**, and **Product/Service reviews**. The sentiments are categorized as **Positive**, **Negative**, and **Neutral**. This project allows users to input a YouTube video URL to analyze its comments, specify a subreddit to analyze posts and comments, and even paste product or service reviews for sentiment classification.

---

## Introduction

The **Sentiment Analysis for YouTube, Reddit, and Reviews** project leverages machine learning algorithms to classify the sentiment of comments from YouTube videos, posts from Reddit, and general product/service reviews. The sentiment is classified into **Positive**, **Negative**, or **Neutral** categories. 

The project is designed to provide users with a simple way to analyze opinions and sentiments from online platforms:

- **YouTube**: Analyze comments from any YouTube video by pasting the URL.
- **Reddit**: Analyze posts and comments from a specified subreddit.
- **Review Analysis**: Paste product or service reviews and obtain sentiment classification for each review.

The sentiment analysis uses **Natural Language Processing (NLP)** techniques, leveraging models such as **VADER** and **scikit-learn** to efficiently classify text data.

---

## Technologies Used

- **Python**: Programming language for development.
- **pandas**: Data manipulation and analysis library.
- **nltk**: Toolkit for natural language processing.
- **VADER**: Sentiment analysis tool for social media text.
- **scikit-learn**: Machine learning library used for model building.
- **Google API Client**: For fetching YouTube comments.
- **PRAW**: Python Reddit API Wrapper for interacting with Reddit.
- **Flask** (Optional): Web interface for easy interaction.
- **Matplotlib**: Data visualization for sentiment distribution.

---

## Features

- **YouTube Comment Sentiment Analysis**: Paste any YouTube video URL to analyze the sentiment of its comments.
- **Reddit Post Sentiment Analysis**: Enter a subreddit name to fetch and analyze posts along with sentiment classification of the comments.
- **Review Sentiment Analysis**: Paste product or service reviews and classify the sentiment as positive, negative, or neutral.
- **Positive, Negative, Neutral Classification**: Each comment, post, or review is classified into one of three sentiment categories.
- **Searchable Subreddit Posts**: Specify the number of posts to analyze from a given subreddit.
- **Visualization**: Sentiment distribution is displayed as a graph for better insight.
- **Real-Time Analysis**: Perform sentiment analysis in real-time for YouTube comments, Reddit posts, and reviews.

---

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/iamamrizejk/Sentiment-Analysis.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd Sentiment-Analysis
    ```

3. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv myenv
    ```

4. **Activate the virtual environment**:

    - On Windows:

      ```bash
      myenv\Scripts\activate
      ```

    - On macOS/Linux:

      ```bash
      source myenv/bin/activate
      ```
---

## How It Works

1. **YouTube**:
   - Fetches comments from the YouTube video URL provided by the user using the **Google API Client**.
   - Preprocesses the text and applies **VADER** and **scikit-learn** models for sentiment classification.
   - Classifies each comment as **positive**, **negative**, or **neutral**.

2. **Reddit**:
   - Fetches posts and comments from the specified subreddit using **PRAW**.
   - Preprocesses the text and performs sentiment analysis on the posts and comments.
   - Classifies the sentiment of each post's comments as **positive**, **negative**, or **neutral**.

3. **Review Analysis**:
   - Takes a list of product or service reviews as input.
   - Preprocesses the review text and applies **VADER** and **scikit-learn** models for sentiment classification.
   - Classifies each review as **positive**, **negative**, or **neutral**.

4. **Visualization**:
   - Displays sentiment analysis results using **Matplotlib** to plot graphs that show the distribution of sentiment across the comments, posts, or reviews.

---

## Acknowledgments

- **Google API Client**: For providing access to YouTube comments.
- **PRAW**: For enabling interaction with Reddit data.
- **VADER**: For efficient sentiment analysis of social media and review content.
- **Libraries**: Thanks to **scikit-learn**, **nltk**, **pandas**, and **matplotlib** for providing robust tools for machine learning and data analysis.

---
