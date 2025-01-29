Intensity-Analysis
Intensity Analysis (model using NLP and Python) The objective of this project is to develop an intelligent system using NLP to predict the intensity in the text reviews. By analyzing various parameters and process data, the system will predict the intensity where its happiness, angriness or sadness. This predictive capability will enable to proactively optimize their processes, and improve overall customer satisfaction.
The Intensity Analysis project focuses on creating both rule-based and deep learning algorithms to effectively identify various emotional intensities (such as sadness, happiness, and anger) within a set of English sentences. The goal is to accurately detect and predict the overall emotional intensity of each sentence. 
Training and validation dataset🔡: 
1- We have 3 base dataset for each intensity {Sad, Happy, Anger} that is used to train the basic model.
2- cleaned_data.csv is more deep processed data after the data clean is done (lemmatization, removal of stopwords, etc).
Comparison of models:
The ML Algorithms used for prediction are listed as follows: Building models using different classifiers (Count vectorizer): Model 1: Multinomial Naive Bayes Classifier - Accuracy 74% Model 2: Linear SVM - Accuracy 78% Model 3: Logistic Regression - Accuracy 86% Building models using different classifiers (TF-IDF vectorizer): Model 1: Multinomial Naive Bayes Classifier - Accuracy 48% Model 2: Linear SVM - Accuracy 50% Model 3: Logistic Regression - Accuracy 48%
During the testing phase of our project, where we evaluated the performance of various machine learning models on data, we discovered that Logistic Regression, combined with Count Vectorization, exhibited the highest accuracy of 86%. This finding suggests that the logistic regression model trained on the counts of words in the text data performed exceptionally well in predicting the intensity of emotions expressed in reviews. The accuracy metric, which measures the proportion of correctly classified instances out of the total instances, serves as a valuable indicator of model performance. In our case, achieving an accuracy of 86% indicates that the logistic regression model with count vectorization effectively captured the underlying patterns and relationships in the text data, enabling accurate predictions of emotion intensity. This result underscores the effectiveness of logistic regression in handling text classification tasks and highlights the utility of count vectorization as a text representation technique. By leveraging these methods, our model demonstrates promising capabilities in accurately predicting emotion intensity in text reviews, thereby empowering businesses to gain valuable insights into customer sentiment and enhance overall customer satisfaction.




Output Prediction of intensity from sentences
**input_text & predicted_emotion**
0 I am so angry at you!!!!! Anger 1 you ve hit a new low with a danger of blm fascist slogan please stop it before too late stop Anger 2 I love my doggg Happy 3 I think i'm gonna be sick :'â€‘( Happy 4 I hate you so much Happy 5 @TheTombert i was watching Harpers Island, lol... there was no vodka involved Happy 6 sometimes i wish things could go back to the way they were the beginning of last summer Sad 7 it's your 18th birthday finally!!! yippeeeee Happy 8 oh no he is hospitalised!!! Anger
 
