# Bag-of-Words-Meets-Bags-of-Popcorn

This is a kaggle tutorial compition problem in which sentiment analysis is to be done. This problem have two goals:

1. Basic Natural Language Processing: Part 1 of this tutorial is intended for beginners and covers basic natural language processing techinques such as "Bag of words" and "TFIDF" as features.

2. Deep learning for text Understanding: we delve into how to train a model using Word2vec and how to use the resulting word vectors for sentiment analysis.

I am using ubuntu so i have installed machine learning library in my system. If you want to install these library follow following steps
step 1 - install jupyter notebook in ubuntu
sudo apt-get -y install python2.7 python-pip python-dev

step 2 - install jupyter notebook
1. sudo apt-get -y install ipython ipython-notebook
2. sudo -H pip install jupyter

open ubuntu terminal and type following commands
#Install machine learning library
1. sudo apt-get install python-pip
2. sudo pip install numpy
3. sudo pip install pandas
4. sudo pip install matplotlib
4. sudo pip install seaborn
5. sudo pip install -U scikit-learn
6. sudo pip install --upgrade tensorflow
7. sudo pip install keras
8. sudo pip install -U nltk

Now run "bag of words.ipynb" file in jupyter notebook

In the zip file i have added two ipython notebook first is bags of words which implement traditional machine learning approaches and second is word embedding which implement our problem using deep learning.

i have submitted my solution in kaggle using results of bags of words ipython notebook.

In bags of words ipython notebook i have used two methods
1. word count as features
2. word count _Tfidf as features
and i have applied mainly two machine learning algorithms on these featurs which are
1. Naive Bayes
2. Logistic Regression

In word embedding i have used embedding layer and LSTM in keras.

Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis.


