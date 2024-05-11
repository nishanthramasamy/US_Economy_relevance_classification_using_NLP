## Determining the relevance of articles relating to US-economy using NLP

### _Overview_:
Analyse 5000+ articles from over 6+ newspapers and find out the whether it is related to US - economy using MLPClassifier

### _Details_:
 1. This repository consists of _us_economy.ipynb_ file, a colab notebook containing the details to analyse the articles from different newspapers. 
 2. After retrieving the dataset, perform preprocessing - converting the text to lowercase, removing stopwords, punctuation, lemmatization,  etc.
 3. Clean the target variable "relevance" to either "yes" or "no", removing "not sure" value.
 4. Then use visualization to get an idea of the dataset and present to stakeholders about the skewness of the dataset eg: here "yes" is around 30 % , this shows the data is more skewed towards "no", so the model is more likely to predict the relevance to "No" about 70% of time.
 5. Then encode the categorical target to numerical one - lone yes to 1 and no to 0.
 6. Then convert the text to vectors using TF-IDF.
 7. Use any any classification model, since the target is binary class. Here I've used MLPClassifier to perform classification.
      * - Skills needed : **_Python_**

