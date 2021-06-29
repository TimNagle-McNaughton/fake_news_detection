# fake_news_detection

The rate of fake news spread has grown beyond the limits of manual moderation and warrants an automated flagging or filtering approach. Here we explore the applicability of several common machine-learning algorithms for automatically detecting a fake news story based on its content.

Using standard natural language processing methods we converted ~20,000 real news stories and ~20,000 fake news stories from [a pre-made dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) into vectors. We then implemented, tuned, trained, and tested five classifiers: Naive Bayes Gaussian, naive Bayes multinomial, K-nearest-neighbors, decision tree, and random forest. Using a 75/25% train/test split of our data, we calculated and compared the accuracy, precision, recall, and F1-scores of the five models.

Adapted from a class project
