# Movie Review Sentiment Analysis

This repository demonstrates movie review sentiment classification using Natural Language Processing (NLP). It employs Random Forest, Multinomial Naive Bayes, and a Pipeline for efficient workflows.

## Features
- Analyze IMDB movie reviews to classify sentiments as positive or negative.
- Preprocess review text with CountVectorizer.
- Train and evaluate Random Forest and Multinomial Naive Bayes models.
- Use a Pipeline for streamlined operations.
- Evaluate models using precision, recall, and F1-score.

## Requirements
The following Python libraries are required to run the notebook:
- pandas
- numpy
- scikit-learn

## Dataset
The dataset is sourced from [IMDB Movie Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download). Ensure the file `IMDB_Dataset.csv` is placed in the `Dataset` directory.

## Clone the repository:
```bash
git clone https://github.com/yourusername/movie-sentiment-analysis.git
```

Navigate to the project directory:
```bash
cd movie-sentiment-analysis
```

Run the notebook:
```bash
jupyter notebook movie_sentiment_analysis.ipynb
```

