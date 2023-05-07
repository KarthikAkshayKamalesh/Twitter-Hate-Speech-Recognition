# Twitter-Hate-Speech-Recognition
Automated classification can be done to detect hate speech from Twitter

## Description of the project

Twitter is one of the most important social networking services which is used to post and send messages known as ”tweets” by the users. Other users on a global scale can read these tweets. Every day, people from various educational backgrounds and cultures express their perspectives on numerous parts of life. As the use of social media grows, everyone appears to believe that they may say or post whatever they want. As a result, there have been conflicts among people. This results in hate speech, which uses aggressive, violent or offensive language based on race or ethnic group(racism) or gender (sexism). Therefore, automated classification can be done to detect hate speech from Twitter. In this approach, we use various Machine learning models such as Knn, Naive Bayes, Logistic regression, SVM, CNN to compare the accuracy and classify whether the tweet is hateful or not.

We chose the Machine learning algorithms that delivered the best results in earlier research after analysing numerous articles relevant to Hate speech identification and also implemented them using Deep Neural networks algorithm. Finally, for all of these methods, we will present a comparison and analysis. Going forward,we will be seeing the Architecture of our proposed system

Dataset : open-source Kaggle (Detecting hatred tweets, provided by Analytics Vidhya ).

## Conclusion

The tweets were classified into one of two categories using different machine learning classifiers like KNN, SVM, Logistic Regression, Multinomial Naive Bayes and Convolutional Neural Network. We used 5 fold crossvalidation on our training data and testing data is used for accuracy. We compared all the model’s accuracy and Logistic Regression got the highest accuracy of 95 percent using count vectorizer whereas SVM got the accuracy of 94 percent in both Count and TF-IDF features. In future, a dataset with a larger number of tweets could be used because it contains more vocabulary and substantial material, It’s challenging to find real-world datasets with accurately specified labels. As a result, we may look into semi-supervised and unsupervised algorithms for detecting mean tweets.

