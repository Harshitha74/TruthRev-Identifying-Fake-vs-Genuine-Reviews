## TruthRev: Identifying Fake vs Genuine Reviews

#Problem Statement:
Online reviews are a major factor in consumer decision-making, but fake reviews distort opinions and reduce trust. This project focuses on detecting whether a review is genuine (human-written) or fake (computer-generated), helping platforms and users make informed decisions.

#Dataset Overview:
The dataset contains thousands of reviews across multiple product categories. Each review includes:
  Review Text: The content of the review.
  Rating: The score given by the reviewer.
  Label: 'OR' for Original (genuine) and 'CG' for Computer-Generated (fake).

#Libraries and Tools:
This project uses the following Python libraries:
  Data Handling: numpy, pandas
  Visualization: matplotlib, seaborn
  Natural Language Processing: nltk, string
  Machine Learning: sklearn (Logistic Regression, SVM, Decision Trees, Random Forest, KNN, Naive Bayes)
  Text Processing: nltk.corpus, warnings
  
#Text Preprocessing:
To prepare the data, the following steps are performed:
  Remove punctuation and numbers
  Convert text to lowercase
  Remove stopwords
  Apply stemming and lemmatization

#Feature Extraction:
Text is converted into numerical features using:
  Bag of Words: CountVectorizer
  TF-IDF: TfidfVectorizer

#Machine Learning Models:
The following models are implemented to classify reviews:
  Logistic Regression
  K-Nearest Neighbors (KNN)
  Decision Tree Classifier
  Random Forest Classifier
  Support Vector Machines (SVM)
  Multinomial Naive Bayes

#Model Performance:
    Model	Accuracy               (%)
    Support Vector Machines	    88.08
    Logistic Regression         86.42
    Multinomial Naive Bayes  	  84.73
    Random Forests Classifier   84.25
    Decision Tree Classifier	  74.02
    K-Nearest Neighbors	        57.93

#Observation: 
  Support Vector Machines achieved the highest accuracy, making it the recommended model for detecting fake reviews.
  

