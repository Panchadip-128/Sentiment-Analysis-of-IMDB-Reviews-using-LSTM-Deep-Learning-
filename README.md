# Sentiment-Analysis-of-IMDB-Reviews-using-LSTM-Deep-Learning

Dataset:
--------
Dataset Used: IMDb Dataset of 50k Movie Reviews
Description: This dataset contains 50,000 movie reviews labeled as positive or negative sentiment.

Installation & Dependancies:
-----------------------------
pip install numpy pandas scikit-learn tensorflow keras


Usage:
-------

Data Preparation:

Download the IMDb dataset from Kaggle using the provided dataset link and access it through the python code directly from kaggle
Preprocess the data by replacing sentiment labels ('positive' and 'negative') with numerical values (1 and 0).

Model Training:

Train the LSTM neural network using TensorFlow/Keras to classify sentiment based on movie reviews.
Evaluate the model's performance using accuracy metrics.

Predictions:

Using the trained model to predict sentiment for new movie reviews.


new_review = "This movie was fantastic. I loved it."
sentiment = predict_sentiment(new_review)
print(f"The sentiment of the review is: {sentiment}")
