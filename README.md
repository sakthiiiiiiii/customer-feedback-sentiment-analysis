# Customer Feedback Sentiment Analysis

An NLP project that analyzes customer phone reviews and predicts their sentiment as Positive, Negative, or Neutral.

## Project Overview

This project demonstrates a basic text-classification workflow:

1. Business understanding
2. Data collection
3. Data understanding
4. Text preprocessing
5. Bag of Words feature extraction
6. TF-IDF feature extraction
7. Logistic Regression model training
8. Sentiment prediction for new reviews

## Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- Google Colab
- Jupyter Notebook

## NLP Techniques

- Lowercase conversion
- URL removal
- Punctuation removal
- Stop-word removal
- Word lemmatization
- Bag of Words
- TF-IDF vectorization
- Logistic Regression classification

## Example Prediction

Input:

```text
Bad camera and battery
```

The notebook uses the trained model to predict the sentiment of the review.

## How to Run

Open the notebook using Google Colab:

1. Download or open the `.ipynb` file.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook**.
4. Upload the notebook.
5. Run the cells from top to bottom.

## Important Note

This notebook currently uses a very small example dataset for demonstration. A larger labeled customer-review dataset should be used for reliable model evaluation.

## Future Improvements

- Use a larger real-world dataset.
- Split the data into training and testing sets.
- Add accuracy, precision, recall, and F1-score.
- Compare multiple machine-learning models.
- Improve handling of emojis and negation.
- Build a web application using Streamlit or Flask.
