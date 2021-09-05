# Sentiment Analysis using Machine and Deep Learning Techniques

## Brief 
A sentiment analysis project in submission to a Natural Language Processing Assignemnt

## Objective 
To classify the overall sentiment of a tweet that is, positive, negative or neutral. 

## Corpus Preprocessing
Regex function as outlined in Table1 (see Sentiment Analysis.pdf)
Lemmatisation with Part-of-Speech tagging using treebank tags is used to transform tokenised content into its root form. 

## Feature Exctraction
The following features are extracted: 
1. Bag of Words
2. TF-IDF (word and n-gram levels) 
3. Gensim word-to-vector
4. Glove Embedding
5. Sentiment by Lexicon (count of positive and negative words) 
6. Sentiment by Emotic (count of happy and sad emoticons)

## Classifiers Used:
1. Naive Bayes Classifier
2. Maximum Entropy Classifier (Logistic Regression)
3. Long-Short Term Memory (LSTM) Classifier

## Results
| Model  | F1-Score |||
|   | Test Set 1 | Test Set 2 | Test Set 3 |
| ------------- | ------------- | ------------- | ------------- |
| Naive Bayes	  | 0.565    | 0.593	| 0.567 | 
| Maximum Entropy	| 0.571  	| 0.597	| 0.551 |
| LSTM	| 0.614  	| 0.641	| 0.578 |

