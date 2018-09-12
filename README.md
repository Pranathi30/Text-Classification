# Text-Classification-
Natural Language Processing competition by Analytics Vidya
I did this problem on Google Colab

Steps followed to solve this problem
1) Lot of data pre-processing is done
 i) Removed http links
 ii) Removed punctuation and apostrophes
 iii)removed @ symbols (tagging)
 iv)removed the top 10 most common words and the bottom 10 least occurred words
 v)removed stop words using NLTK's corpus package
 vi)standardized words and removed stemming words
2) count vectorizer, word level TF-IDF vectors, character level TF-IDF vectors, N-gram level (range (1,2)) TF-IDF vectors are extracted as features
3) different classifiers such as Naive Bayes, SVM, Logistic Regression, Random Forest, XGBoost and shallow Neural Networks are built and XGBoost for character level TF-IDF vectors as features found to be the best model with F-1 score being 0.87
