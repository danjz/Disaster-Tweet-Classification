# Disaster-Tweet-Classification

A final year project for my Computer Science degree at Cardiff University.

Social media platforms play a critical role during emergency disaster response events. These platforms facilitate a powerful communication outlet that anyone can utilize during any type of disaster emergency. This project explores natural language processing and  machine learning approaches to classifying twitter ‘tweets’ as either relating to or not relating to an actual real-life disaster. Twenty different models have been developed and evaluated to perform the classification. Each model consists of one of four different vectorization techniques (Bag-of-Words, TF-IDF, pre-trained Word2Vec, trained Word2Vec) and one of five different machine learning classifiers (SVM, Logistic Regression, Random Forest, Gaussian Naïve Bayes). The developed models achieved an average accuracy of 80% with the top performing model utilizing the SVM classifier and a Word2Vec embedding trained on this project’s dataset.

The dataset used was created by crowdflower and can be accessed here: https://data.world/crowdflower/disasters-on-social-media
