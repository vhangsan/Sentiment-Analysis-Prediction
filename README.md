# Book Review Sentiment Analysis 

### Project Overview
As part of my Machine Learning Foundations course with Cornell tech, I worked on a project focused on sentiment analysis of book reviews. The goal was to classify whether a review is positive or negative. The analysis is performed by training and optimizing multiple machine learning models using feature-engineered text data. By leveraging sentiment analysis, we can gain insights into readers' opinions towards different books.

### Data
The dataset, [bookReviewsData.csv], consists of book reviews labeled as either positive or negative. The text data was preprocessed by:
* converting the text to lowercase
* removing punctuation
* tokenizing and vectorizing using TF-IDF (Term Frequency-Inverse Document Frequency)

### Models Used
Three different machine learning models were trained and optimized for sentiment classification:
1. Logistic Regression
2. Support Vector Classifier (SVC)
3. Random Forest
   
Each model was trained on the preprocessed review text, and their performances were evaluated using various metrics, including accuracy, precision, recall, and F1-score.

### Optimization
To improve model performance, hyperparameter tuning was performed using GridSearch, which helped find the optimal parameter values for each model.

### Results
* The sentiment analysis models achieved over 80% accuracy in identifying positive and negative reviews. 