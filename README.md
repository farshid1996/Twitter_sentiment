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

# Creating an evaluation function for our model experiments
In this section, the function shows `accuracy`, `precision`, `recall`,and 'f1' scores.

# Model 1: A simple dense model
Model 1 is simple model with GlobalAveragePooling1D and a Dense layer.
![Screenshot (18)](https://user-images.githubusercontent.com/63876585/222383923-4b4720e1-daad-4d65-9e85-6bda360e30dc.png)

## compare_baseline_to_new_results
This function helps to compare two models results.

# Visualizing learned embeddings
First, pulling out an Embedding layer from the Model 1 layers.
Secondly, Download the `vector.tsv`, 'metadata.tsv'. 
Finally, upload those file in tensorflow projection 
