# Natural-Language-Processing-with-Disaster-Tweets

This project is a solution to the Kaggle competition **[Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/overview)**. The goal is to classify tweets as related to real disasters or not using machine learning and natural language processing (NLP) techniques.

## Competition Overview

In times of emergencies, Twitter has become an essential communication platform. However, distinguishing tweets that report actual disasters from those using metaphorical language can be challenging. 

The dataset includes:
- **10,000 tweets**, each labeled as describing a real disaster (1) or not (0).
- Metadata for each tweet, including keywords and locations (which may be blank).

Participants are evaluated using the **F1 score**.

## Dataset

The dataset consists of the following files:

- `train.csv`: Training data with labeled tweets.
- `test.csv`: Test data for prediction.
- `sample_submission.csv`: Example submission format.

### Columns:
- `id`: Unique identifier for each tweet.
- `text`: The text of the tweet.
- `location`: Location from which the tweet was sent (may be blank).
- `keyword`: Specific keyword from the tweet (may be blank).
- `target`: (In `train.csv` only) Denotes whether the tweet is about a real disaster (1) or not (0).

## Solution Overview

The solution is implemented in the Jupyter Notebook:
- **`natural-language-processing-with-disaster-tweets.ipynb`**: Contains the complete code and explanation of the approach.

Key highlights:
- Text preprocessing and feature extraction.
- Use of machine learning models for classification.
- Optimization for improved F1 score.

## Results

- **Leaderboard Score**: `0.82010`
- **Position**: `213/810`

![Leaderboard](https://github.com/user-attachments/assets/ab62e89e-ee74-4680-8703-71ef1610452f)


## Tools and Libraries Used

- Python
- Jupyter Notebook
- Libraries: Pandas, NumPy, Scikit-learn, NLTK, and more.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nlp-disaster-tweets.git
   ```
2. Navigate to the project directory:
   ```bash
   cd nlp-disaster-tweets
   ```
3. Open the notebook:
   ```bash
   jupyter notebook natural-language-processing-with-disaster-tweets.ipynb
   ```
4. Follow the steps in the notebook to preprocess data, train models, and generate predictions.

