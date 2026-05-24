# IMDB Review Sentiment Analysis

A simple NLP and Machine Learning project to classify IMDB movie reviews as positive or negative.

## What I Used

- Python
- Pandas
- NLTK
- Scikit-learn

## Steps Performed

1. Text preprocessing
   - Removed special characters
   - Converted text to lowercase
   - Removed stopwords
   - Applied stemming

2. Vectorization
   - Used `CountVectorizer`
   - Used `TfidfVectorizer`

3. Model Training
   - Logistic Regression
   - Random Forest
   - Decision Tree
   - KNN

4. Final Prediction
   - Selected the best model based on classification report
   - Predicted sentiment for new reviews

## Output

The model predicts whether a movie review is:

- Positive
- Negative
