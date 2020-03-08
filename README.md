# Detection_of_fake_news
Given a dataset of news consisting of the title and description about the news and corresponding label classifying it as Fake or Real training a model and testing the model and checking its accuracy.


As the data is textual I have used TfidfVectorizer which converts the text into a tfidf matrix of the words present in the text represented by set of features. 

The training is converted into this form and then passed onto PassiveAggressiveClassifier, Logistic Regression and Stochastic Gradient Descent for the purpose of classifying and predicting. All the models gives an accuarcy of about 92% which is good also the confusion matrix is calculated.

Reference: https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/
