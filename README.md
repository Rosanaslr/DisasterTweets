# Disaster Tweets
Solution to kaggle competition "Natural Language Processing with Disaster Tweets" (https://www.kaggle.com/c/nlp-getting-started).

## Dependencies
* Python 3
* Jupyter Notebook

## How to Run
Import `DisasterTweets.ipynb` file to jupyter notebook and run.

## Solution
* Imported training dataset;
* Removed numbers, symbols;
* Applied tokenization, stemming;
* Removed stopping words;
* Trained linear SVC model using train data;
* Calculated accuracy score and plotted confusion matrix;
* Imported test dataset;
* Removed numbers, symbols;
* Applied tokenization, stemming;
* Removed stopping words;
* Predicted tweet disaster using test dataset;
* Created submission file;