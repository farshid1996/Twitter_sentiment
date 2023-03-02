# Twitter_sentiment
Twitter Sentiment Analysis to label tweets in diaster or not diaster

# DataSet
Use this link[https://storage.googleapis.com/ztm_tf_course/nlp_getting_started.zip] to get dataset which is shown in below.
Targets are 1 or 0, respectly means diaster or not diaster.
![Screenshot (17)](https://user-images.githubusercontent.com/63876585/222380849-c6e233ef-8151-4299-a85b-07a14d21ea3d.png)

## Split dataset
After shiffling the data, the dataset is splitted into train and test data. The splitting ratios are 70 percent for train and 30 percent for test data.

# Converting text into numbers
To use data, the texts are converted to number using TensorFlow TextVectorization library.

# Creating an Embedding using an Embedding Layer
To create the Embedding layer, the Embedding function from tensorflow layers has been used.

# Models
To get the base evaluation, the MultinomialNB from sklearn.naive_bayes is good. 

## 
