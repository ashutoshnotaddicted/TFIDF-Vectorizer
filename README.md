# TFIDF-Vectorizer
First, I need to implement both the fit and transform methods for my custom TF-IDF Vectorizer.

After fitting the data, I will print out the alphabetically sorted vocabulary and compare it with the feature names from scikit-learn's TF-IDF Vectorizer to ensure they match.

I will also print out the IDF values from my implementation and compare them with the IDF values from scikit-learn's TF-IDF Vectorizer to ensure they match.

Once I have confirmed that my vocabulary and IDF values match scikit-learn's implementation, I will proceed to the next steps.

To ensure my output matches scikit-learn's TF-IDF Vectorizer, I need to make sure that the output of my implementation is a sparse matrix. Before generating the final output, I will normalize the sparse matrix using L2 normalization. I will refer to scikit-learn's documentation on how to perform this normalization.

After completing the above steps, I will print the output of my custom implementation and compare it with scikit-learn's implementation of the TF-IDF Vectorizer.

To check the output of a single document in my collection of documents, I can convert the sparse matrix related only to that document into a dense matrix and print it.
First, I will modify the fit and transform methods of my custom TF-IDF Vectorizer to limit the vocabulary to only the top 50 terms based on their IDF scores. This means that the output will have exactly 50 columns, and the number of rows will depend on the number of documents in the corpus.

After fitting the data, I will sort the vocabulary based on the descending order of IDF values. I will then print out the words in the sorted vocabulary to verify that it contains only 50 terms. Additionally, I will print the IDF values for each term in the vocabulary.

To ensure consistency with scikit-learn's TF-IDF Vectorizer, I will make sure that the output of my implementation is a sparse matrix. Before generating the final output, I will normalize the sparse matrix using L2 normalization. I will refer to scikit-learn's documentation on how to perform this normalization.

To check the output of a single document in my collection, I will convert the sparse matrix related only to that document into a dense matrix and print it. The dense matrix should contain 1 row and 50 columns, representing the TF-IDF values for the top 50 terms.
