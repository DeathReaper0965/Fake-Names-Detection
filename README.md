# Fake-Names-Detection

Start by running the whole Jupyter Notebook, at the end there is a sample code to let you get aquainted with how to use the best model out of all the experimental models that are used in the Notebook to make the best of predictions, there by classifying the names with best accuracy of 93.64 %

Models tested for classification of names are: **MultinomialNB, Count Vectorizer, TfIdf Vectorizer, DecisionTreeClassifier, ElasticNet, GRU RNN using TensorFlow**

The Models Count Vectorizer and TfIdf Vectorizer gave pretty amazing results but found out that they generally are overfitting the data.

The Best Model found was a Custom-Made 6 layered TensorFlow Sequential Model with **1 Embedding Layer and 3 GRU(Gated Recurrent Unit) layers.**
