# amazon_alexa_sentiental-analysis
This sentimental analysis helps in analysing the reviews of the different type of amazon alexa bought by the customers and finding the best model by checking the accuracy of different models

The needed libraries are imported [nltk,re].
The reviews are first tokenized and they are lemmatized.
After lemaatizing ,the text is visualized by the method of bag of words.
Once the preprocessing is done,the classification models are built.
The various classification model is compared by their accuracy score.
After comparing, the decision tree is found as the best model with 93% of accuracy
