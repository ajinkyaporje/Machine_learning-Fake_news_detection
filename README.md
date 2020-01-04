# Machine_learning-Fake_news_detection
Fake news are basically hoaxes and are generally spread through social media or any online social networking portals. 
These are generally targeted for political purpose or to gain certain agenda. 
We use python as a tool to determine the real and fake news.


The dataset used here is news.csv provided by dataflair.

The libraries used consist of following.
1) Pandas
2) Numpy
3) Itertools
4) sklearn

We use TfidfVectorizer to convert a collection of raw documents into a matrix.
We also use PassiveAggressiveClassifier for classification.

Finally we check the accuracy of the model we built along with a confusion matrix