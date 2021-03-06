# Yelp Restaurant Sentiment Analysis

Yelp is a popular app/website that allows users to write reviews and rate businesses based on a star rating of 1-5.  This helps users see which businesses are good and helps businesses understand their customers. However, many businesses have hundreds of reviews left by customers, so it is tedious to shift through each review manually. This is where Natural Language Processing (NLP) comes in. In this project, we built a text classifier that focuses on restaurant reviews using Python’s Pandas, NLTK, and Scikit-Learn libraries.  After neccesary data cleaning and preparation, the dataset is trained 3 different deep learning models: RNN, Bi-directional LSTM, and CNN+LSTM.  The objective is to predict whether a review is positive or negative based on the context of the reviews. 

# Results 
The first photo is the Bi-directional LSTM Training/Validation Loss and Accuracy. The second photo shows a model comparison of the 3 deep learning models. 

![alt text](https://github.com/kristienguyen100/Yelp_NLP_Restaurants/blob/main/Pics/Bi-directional%20LSTM%20result.png)

![alt text](https://github.com/kristienguyen100/Yelp_NLP_Restaurants/blob/main/Pics/Model%20Comparison.png)

