<h1> Sentiment Analysis for Amazon Product Reviews </h1>
<h2>📚 Overview </h2>
This project aims to develop a sentiment analysis model tailored specifically for Amazon product reviews. By analyzing customer sentiment expressed in ratings and text, the goal is to uncover insights into consumer experiences, product preferences, and overall satisfaction.

<h2>🎯 Objective</h2>
The primary objective is to create a model that effectively classifies sentiments expressed in Amazon reviews, allowing for a better understanding of user feedback and improving product recommendations.

<h2>📊 Dataset </h2>
The project utilizes a dataset of Amazon product reviews, comprising a comprehensive collection of real customer feedback. A balanced sample of 60,000 reviews was created by randomly selecting 20,000 reviews from each star rating category.

<h2>🔧 Key Steps</h2>
<h3>1. Data Preparation</h3>
Loaded the dataset using the Pandas library.
Focused on relevant columns, including star ratings and review content.
<h3>2. Data Cleaning</h3>
Cleaned the review text by removing non-alphabetical characters, expanding contractions, converting text to lowercase, and eliminating URLs and HTML tags.
<h3>3. Data Preprocessing & Feature Extraction</h3>
Utilized NLTK for further preprocessing, removing stop words.
Employed the Word2Vec model to generate 300-dimensional word embeddings.
Extracted features using the TF-IDF method to create numerical representations of the text data.
<h3>4. Model Training & Evaluation</h3>
Trained and evaluated various models, including Perceptron, Support Vector Machines (SVM), and Recurrent Neural Networks (RNN).
Assessed model performance using metrics such as accuracy, precision, recall, and F1-score.
<h2>📈 Results</h2>
The model utilizing TF-IDF features outperformed Word2Vec features, achieving the following metrics:

-Precision: 74.17%

-Recall: 74.38%

-F1 Score: 74.27%

Best Accuracy: 74.38% (SVM with TF-IDF)
<h2>🔍 Conclusion</h2>
The findings highlight the importance of feature extraction methods and classification algorithms in sentiment analysis. TF-IDF-based models demonstrated superior performance compared to Word2Vec and RNN models in accurately predicting sentiment.

<h2>🛠️ Technologies Used</h2>

Python

Pandas

NLTK

Word2Vec

Scikit-learn
