# Amazon Reviews Sentiment Analysis

This project analyzes Amazon product reviews to classify them as positive or negative using Natural Language Processing (NLP) and Logistic Regression.

## Dataset
- Amazon reviews dataset loaded from Google Drive.

## Steps
1. **Data Preprocessing**  
   - Extracts integer ratings and review counts.  
   - Cleans review text (removing punctuation, stopwords, etc.).  
   - Creates a binary label: positive (rating ≥ 4) or negative (rating ≤ 3).

2. **Exploratory Data Analysis (EDA)**  
   - Visualizes rating distribution.  
   - Identifies common words in positive vs. negative reviews.

3. **Modeling**  
   - Trains a Logistic Regression model using selected words as features.  
   - Evaluates performance with accuracy, precision, recall, and false positive rate.  
   - Compares original and tuned models.

4. **Visualization**  
   - Confusion matrix, predicted probabilities, and incorrect vs. correct predictions.

## Dependencies
- Python, pandas, numpy, seaborn, matplotlib, nltk, scikit-learn

## Usage
Run the notebook or script to process the data, train models, and evaluate results.
