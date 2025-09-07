# SMS-Spam-Classification
Authors: Advithi Kethidi, Kalyani Mantirraju, Sneha Gurug, Taha Mohiuddin, Jonathan Jin, and Chris Woo

This notebook explores SMS spam detection by analyzing textual characteristics of SMS messages. Our goal for this project is to identify similarities amongst SMS spam and see if we can create a classification sorting out ham and spam messages.
Using a dataset of various SMS messages (labeled ham or spam), we performed exploratory data analysis (EDA) to identify distinguishing features between ham and spam messages. After performing EDA, we conducted technique tests such as sentiment analysis, frequency analysis with bayes classifier, and more to further distinguish spam and ham attributes. Through visualizations and classification techniques, this notebook analyzes effective spam detection models.   


###Questions we have are:

*   What keywords imply an SMS message is spam?
*   Is there a sense of urgency in wording for SMS spam?
*   Can we create a classifier that sorts out ham and spam accurately?

###Dataset
The dataset we are using is a collection of SMS spam and ham messages collected.
Dataset Link:

https://archive.ics.uci.edu/dataset/228/sms+spam+collection

##Techniques we want use
**Sentiment Analysis**:
We want to extract and analyze keywords in SMS spam to understand the emotions the messages may evoke/imply.

**Frequency Analysis**:
We want to identify words that appear frequently in spam messages. This can indicate a pattern that may help our model identify spam messages.

**Word Length Analysis**:
We want to identify long texts that include links or codes because it can be an indicator of spam. Long URL’s or promotion codes can be a sign of spam as well.

**Cosine Similarity + KNN**
We want to use cosine similarity as our distance measurement in our implementation of KNN. Our model will predict whether or not certain messages are considered HAM or SPAM.

**Naive Bayes**
We want to use Naive Multinomial Bayes to identify the probabilities of words and messages to be classified as HAM or SPAM.

**Logistic Regression**
We want to classify SMS messages as spam or ham using logistic regression. By analyzing word frequency and patterns in messages, we can train the model to distinguish spam messages with high accuracy.


