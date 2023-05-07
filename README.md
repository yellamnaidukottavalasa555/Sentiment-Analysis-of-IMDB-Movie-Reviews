# Sentiment-Analysis-of-IMDB-Movie-Reviews

The goal of sentiment analysis is to determine the attitude, opinion, or sentiment of the writer towards a particular topic, product, or service. Sentiment analysis of IMDB movie reviews involves analyzing these user-generated reviews to determine the sentiment towards a particular movie.

In the context of IMDB movie reviews, sentiment analysis involves classifying the reviews as positive, negative. This project is focused on comparing different text representations and learning models on a classification task.

In this project, I worked with a large supervised dataset of English IMDB Movie reviews. I explored three text representation strategies and four classifiers to perform sentiment analysis on the movie reviews. The aim was to compare the performance of different models and select the best-performing models.

### Text Representation Strategies

**1.Bag-of-Words (BoW):** This approach represents each document as a vector of word frequencies, ignoring the order in which the words occur.

**2.TF-IDF:** This approach is similar to BoW, but it also considers the importance of each word in the document and across the corpus.

**3.Doc2Vec (d2v):** This approach represents each document as a vector in a high-dimensional space, where similar documents are located closer together.

### Classifiers

**1.Logistic Regression**

**2.Decision Tree Classifier**

**3.Random Forest Classifier**

**4.Multinomial Naive Bayes Classifier**

### Base Models

First implemented the base models for each combination of text representation strategy and classifier without any tuning. I used evaluation metrics such as accuracy, precision, recall, and F1-score to compare the performance of these models.

### Tuning Models

Then I observed that the models needed tuning to improve their performance. I used grid search and cross-validation techniques to tune the hyperparameters of each model.

### Comparing Models

Compared the performance of each pair of models using hypothesis testing. I used a significance level of 0.05 and calculated the test statistic and critical value to determine whether there was a statistically significant difference in performance between of the two models.

### Conclusion

Based on evaluation metrics and hypothesis testing, I selected LR, MNB with TF-IDF features are the best-performing models and then RFC gives better results with TF-IDF for sentiment analysis on the IMDB Movie reviews dataset.
