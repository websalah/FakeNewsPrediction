# Fake News Detection Project
This is a simple NLP (Natural Language Processing) project that checks whether a news article is Real or Fake.
The model was trained using the WELFake dataset, which has more than 72,000 news articles.

WELFake dataset from kaggle: [Click link](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification/)

The project uses:
* text cleaning
* TF-IDF vectorization
* Logistic Regression

The final model got about 95% F1-score.

---

## Results

* Training Accuracy: 95.88%
* Test Accuracy: 94.73%

### Classification Report

| Class | Precision | Recall | F1-Score | Support |
|---|---|---|---|---|
| Real (0) | 0.95 | 0.94 | 0.95 | 7,006 |
| Fake (1) | 0.94 | 0.96 | 0.95 | 7,421 |
