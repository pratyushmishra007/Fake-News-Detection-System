# Fake News Classification using NLP, Machine Learning, and Deep Learning (LSTM)

## Project Overview

Fake news, often spread through traditional and social media, contains deliberate disinformation or hoaxes. This project employs various NLP-based machine learning and deep learning techniques, including BERT, to identify fake news from headlines. Fake headlines typically present misleading or untrue information, often referred to as **“clickbait”**.

Key components of this project include:

- Exploratory data analysis & feature engineering using NLP
- Machine learning modeling with text-based features
- Deep learning modeling (LSTM) with text-based features
- BERT model building with text-based features

## About the Data

The dataset used is the [ISOT Fake News Dataset](https://drive.google.com/open?id=1IoTRrJNDJqvaG3hnUpnHQyGvPAJbO8y3), containing both fake and real news articles. Real articles were sourced from Reuters.com, while fake articles were collected from unreliable sites flagged by Politifact and Wikipedia. The dataset includes articles mainly focused on political and world news topics, split into two CSV files:

- `True.csv`: 12,600+ articles from Reuters
- `Fake.csv`: 12,600+ articles from fake news sources

Each article contains:
- **Title (News Headline)**
- **Text**
- **Type (REAL or FAKE)**
- **Publication Date**

## Word Cloud of Dataset

The word cloud visualizes the most frequent words in the corpus. Larger words appear more frequently. Common words in fake news include Video, Obama, Hillary, Trump, and Republican, while real news often features Trump, White House, North Korea, and China.

## Installations

Ensure Python 3.7x and the following libraries are installed:
- [Numpy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Seaborn](https://seaborn.pydata.org/)
- [KTrain (for BERT)](https://pypi.org/project/ktrain/)
- [NLTK](https://www.nltk.org/install.html)
- [NLTK Data](https://www.nltk.org/data.html)
- [Keras](https://keras.io/)
