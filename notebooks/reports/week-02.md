# Week 02 Progress Report

## Completed This Week

* Performed text preprocessing (cleaning, tokenization)
* Removed special characters, hashtags, mentions
* Converted text into numerical features using TF-IDF
* Built baseline model using Logistic Regression
* Trained and evaluated baseline model

---

## Important Files Added
notebooks/preprocessing and baseline_model.ipynb
src/preprocess.py
src/baseline.py
results/baseline_metrics.txt



## Experiments and Results

Baseline model (Logistic Regression) was trained using TF-IDF features.

Initial results:

Accuracy: 0.81
Macro F1-score: 0.73
Weighted F1-score: 0.80

Model performs better on negative sentiment than neutral class.

## Problems Encountered

* Class imbalance affects neutral class prediction
* Text contains noise (emojis, links, mentions)
* Need better feature representation for deep learning model


## Plan for Next Week

* Build LSTM model
* Improve embeddings (Word2Vec or GloVe)
* Start deep learning training
