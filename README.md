NLP with Disaster Tweets Competition (Kaggle)
This project is dedicated to the "Twitter Disaster Detection" competition hosted on Kaggle, focusing on Natural Language Processing (NLP) techniques to detect real-time emergencies from tweets.

Competition Description
Twitter serves as a crucial communication channel during emergencies, enabling individuals to report incidents in real-time via smartphones. Consequently, there's a growing interest from various agencies, including disaster relief organizations and news agencies, in programmatically monitoring Twitter for emergency situations.

Link to Competition: Twitter Disaster Detection

Required Libraries
Ensure the following libraries are installed to execute this project:

pandas
re
warnings
nltk
stopwords from nltk.corpus
PorterStemme from nltk.stem
train_test_split from sklearn.model_selection
CountVectorizer from sklearn.feature_extraction.text
accuracy_score, f1_score, confusion_matrix, classification_report from sklearn.metrics
MultinomialNB from sklearn.naive_bayes
RandomForestClassifier from sklearn.ensemble
VotingClassifier from sklearn.ensemble
Repository Files
readme.md: The current README file.
Submission Result on Kaggle.png: Screenshot of the competition result on Kaggle (score: 0.79558).
nlp_disaster_tweets_competition.ipynb: Jupyter notebook containing the project development.
sample_submission.csv: Sample CSV file demonstrating the required format for submission on Kaggle.
submission_ensemble.csv: CSV file of the final project submission for Kaggle.
test.csv: CSV file containing test data.
train.csv: CSV file containing training data.
Feel free to explore the notebook (nlp_disaster_tweets_competition.ipynb) for detailed insights into the project development and methodologies employed. If you have any questions or suggestions, don't hesitate to reach out!
