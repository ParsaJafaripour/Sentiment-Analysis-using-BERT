# Sentiment Analysis using BERT

This project is a sentiment analysis tool built using a pre-trained BERT model from Hugging Face's `transformers` library. The project involves scraping reviews from a webpage, processing the text, and assigning a sentiment score to each review. The project is implemented in a Jupyter notebook using Google Colab.

## Project Description

This project leverages the `nlptown/bert-base-multilingual-uncased-sentiment` model, which is capable of classifying the sentiment of text in various languages. The project includes web scraping, text processing, and sentiment analysis on real-world data, showcasing the application of natural language processing (NLP) techniques in sentiment analysis tasks.

### Features:
- **Web Scraping**: Extracts user reviews from a Yelp page using `requests` and `BeautifulSoup`.
- **Sentiment Analysis**: Uses a pre-trained BERT model to classify sentiment on a scale from 1 to 5.
- **Data Processing**: Reviews are processed and loaded into a DataFrame, where each review is scored for sentiment.

## Installation

To run this project, you'll need to install the necessary dependencies. If you're running this on Google Colab, use the following:

```bash
!pip install transformers
!pip install torch
!pip install requests
!pip install beautifulsoup4
!pip install pandas
```

## Usage

1. **Import and install dependencies**: The project requires libraries such as `transformers`, `torch`, `requests`, `BeautifulSoup`, and `pandas`.

2. **Load the pre-trained BERT model**: The BERT model from the `nlptown` repository is used for sentiment classification.

3. **Web scraping**: Reviews are scraped from a Yelp page.

4. **Sentiment analysis**: Each review is tokenized and scored using the BERT model.

## Files Included

- **Sentiment Analysis.ipynb**: The Jupyter notebook containing the full implementation of the sentiment analysis project.

## Model

The model used in this project is `nlptown/bert-base-multilingual-uncased-sentiment`, which is a pre-trained BERT model for sentiment analysis.

## Acknowledgments

- The project utilizes the `transformers` library by Hugging Face.
- Special thanks to the creators of the BERT model and the NLP community for their open-source contributions.
