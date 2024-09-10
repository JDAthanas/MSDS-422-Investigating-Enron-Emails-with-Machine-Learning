# MSDS-422-Investigating-Enron-Emails-with-Machine-Learning
Investigating Enron email dataset to flag any negative or fraudulent activity within the emails 

Data

The Enron dataset consists of over 500,000 employee emails, but for this analysis we processed 10,000 emails at a time. 

Modeling

We parsed the data into one file including the fields: 'to','from', 'date', 'subject', and 'body. Cleaned body of the emails by removing low importance words and tokens. Created three new fields after running a text analysis in EDA - 1. Sentiment score, 2. Subjectivity Score, and 3. Flagged Emails that contained key terms identified through the EDA process as negative or signs of fraudulence. Then split the data into testing and training sites to test our machine learning models: LogisticRegression, RandomForest, GradientBoostingm Support Vector Classifier (SVC).
