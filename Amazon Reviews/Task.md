Dataset: Amazon reviews dataset; This dataset was created from the scraped reviews from products in Amazon, it contains 17000+ records attached with “amazon_reviews.csv”. The classes are three in number namely; Negative Reviews, Neutral Reviews, Positive Reviews.
 
Requirements:
Data Pre-processing (if needed): to clean your data and provide a valid dataset for the models to be trained, like removing stopwords using NLTK.
 
Data Splitting: apply data splitting for your; 80% as training set and 20% as a validation set.

Word Embedding: build your vocabulary by extracting and indexing unique words, convert each review to a sequence of indices, then apply sequence padding to have all sequences of the same length in preparation for input to the embedding layer.

Model Training: You will train two models simpleRNN and LSTM and print the accuracy for each model on testing data.

Additional:
 1. Allow the user to input a new review and predict the result.
 2. Provide a report that shows model summary of each model and the best hyperparameters for each model (splitting ratio, sequence padding length … ) with a table showing the accuracy against each parameter (i.e. 80% 20% ratio, 70% 30% ratio, and same for sequence padding length).