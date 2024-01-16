# Financial Text Classification

The project involves text classification, specifically focusing on financial news categorization. The primary objective is to build a classifier using the Naive Bayes algorithm to predict the category of financial news articles. The dataset used for training and testing is sourced from the Reuters corpus, encompassing categories such as earnings ('earn'), acquisitions ('acq'), and natural gas ('nat-gas'). The implementation includes the following key steps:

1. Data Retrieval and Exploration:

* Downloading the Reuters dataset using the NLTK library.
* Exploring and printing all possible categories available in the dataset.

2. Data Preparation:

* Loading a subset of the Reuters dataset, focusing on specific financial categories.
* Creating a dataset by pairing raw document text with corresponding category labels.
* Shuffling the dataset for randomness.

3. Data Splitting:

* Separating the dataset into training and testing sets using the train_test_split function.

4. Text Vectorization:

* Utilizing the CountVectorizer to convert the raw text data into numerical feature vectors.
* Vectorizing both the training and testing datasets.
  
5. Model Training:

* Implementing a Multinomial Naive Bayes classifier for training on the vectorized training data.

6. Model Evaluation:

* Testing the trained classifier on the testing set.
* Calculating and displaying the accuracy of the classifier.
* Generating a classification report providing detailed performance metrics.

7. Prediction on New Articles:

* Providing sample news articles for prediction, including examples of earnings, acquisitions, and a generic test article.
* Vectorizing the new articles and predicting their categories using the trained classifier.
* Displaying the predicted labels for each article.

The project emphasizes the application of machine learning techniques for classifying financial news articles into relevant categories, showcasing the implementation and evaluation process using the Naive Bayes algorithm and the Reuters dataset.
