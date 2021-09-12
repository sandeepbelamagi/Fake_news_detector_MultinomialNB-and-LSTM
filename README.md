# Fake_news_detector_MultinomialNB
for data set please follow this link: https://www.kaggle.com/c/fake-news/data

It's a NLP project solved with machine learning module called MultinomialNB
steps followed:
1. Load the data
2. Import the required libraries
3. preprocessing Data
    1. cleaning the null values
    2. removing the unwanted text, dots etc.
    3. Vectorizing the cleaned data with TF-IDF technique
4. training and Testing the model
5. Result with Accuracy of 91% (MultinomialNB) and 99% (LSTM)

Multinominal model accuracy is by taking all columns but LSTM is only for title and author columns beacuse while taking all the columns the time taken is more.
