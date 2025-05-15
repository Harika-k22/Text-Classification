Text classification is the process of assigning predefined categories or labels to textual data based on its content. 
One of the most popular and effective techniques for this task is Naive Bayes
Naive Bayes assumes that the presence of a particular word in a document is independent of the presence of any other word,
given the category. Despite this "naive" assumption of independence, it performs remarkably well in practice, 
especially for large-scale text classification problems like spam detection, sentiment analysis, topic categorization,
and language identification.

The steps involved are:

Text Preprocessing: The input text is cleaned and tokenized. 
Common preprocessing steps include removing stop words, converting to lowercase, stemming/lemmatization,
and vectorizing the text (e.g., using Bag of Words or TF-IDF).

Training the Model: Using a labeled dataset, the algorithm learns the probability of each word occurring in documents of 
each class, and the prior probability of each class.

Prediction: For a new, unseen document, the algorithm calculates the posterior probability
for each class and assigns the class with the highest probability.
