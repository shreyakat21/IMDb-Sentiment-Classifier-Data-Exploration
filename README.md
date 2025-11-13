# IMDb Sentiment Classifier – Data Exploration

## What I Did

- Loaded the IMDb dataset (50,000 reviews with sentiment labels)
- Checked for null values and cleaned the data (no missing values)
- Plotted class distribution (balanced dataset)
- Looked at review lengths and plotted a histogram
- Displayed a few example reviews from both positive and negative classes
- Created a word cloud to see the most common words (with stopwords removed)

## Visuals Generated

- Bar chart: number of positive vs negative reviews
- Histogram: length of reviews
- Word cloud: common words in the reviews

## Dataset Info

- Dataset: [Kaggle - IMDb 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Two columns: `review` (text), `sentiment` (label)

## Requirements

Make sure you have Python 3.7+ and the following packages:

```bash
pip install
pandas
numpy
matplotlib
seaborn
wordcloud
nltk

You’ll also want to download NLTK stopwords by running this once in your notebook:

python
Copy
Edit
import nltk
nltk.download('stopwords')




