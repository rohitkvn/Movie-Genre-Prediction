# Predictive Analytics with Spark

# Project Description
- The objective of the project is to implement a movie genre prediction model using
Apache Spark
- The dataset provided [here](https://github.com/prabha1729/Multi-Label-Movie-Genre-Prediction/blob/master/train.csv) contains information about movies.
- train.csv has movie summaries of around 31K movies along with their genres. You will
use this to train your predictive analytics model
- test.csv has just plot summaries. You will be predicting the genre of these movies
- The task of predicting the genre is essentially a multi-label classification problem. A
movie can have multiple genres associated with it. Your model should be able to predict
all the genre associated with the movie
- The mapping of the genre to the string index should be generated in .csv format. For example
presence of genre ‘Drama’ is indicated by a ‘1’ in the first position of the prediction string
and an absence of this genre is indicated by ‘0 in the first position

## Reach out to me
[<img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />](https://www.linkedin.com/in/prabhakargaddam/)
[<img align="left" alt="Gmail" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />](<mailto:prabhakargaddam1729@gmail.com>)

<br/>

## Basic Model (term-document matrix)

- Analyze the data and preprocess it if needed
- Create a machine learning model (use any algorithm) in spark to use the information
provided in the train set to predict the genres associated with a movie.
- You should create a term-document matrix from the plots and use these as feature
vectors for the machine learning model.
- CountVectorizer Demo

![CountVectorizer Demo](https://github.com/prabha1729/Multi-Label-Movie-Genre-Prediction/blob/master/Part-1.gif)
## TF-IDF to improve the model
- Focussing on the summary of the movie, implement Term Frequency-Inverse Document
Frequency (TF-IDF) based feature engineering technique to improve the performance of
the model
- Ideally, your model should improve performance from the previous step
- TF-IDF Demo

![TF-IDF Demo](https://github.com/prabha1729/Multi-Label-Movie-Genre-Prediction/blob/master/Part-2.gif)
## Feature Engineering (Word2vec)

- Implement any one of the modern text-based feature engineering methodology to
improve the performance of the model
- Custom feature engineering would be deemed successful only if the model performs
better than the model of part 2
- Word2Vec Demo

![Word2Vec Demo](https://github.com/prabha1729/Multi-Label-Movie-Genre-Prediction/blob/master/Part-3.gif)
## Execution

- Upload train.csv ,test.csv and jupter notebooks to [Google Colab](https://colab.research.google.com/) .
- After running for each notebook for certain time say (50 mins) a file with extension .csv will be generated containg the predictions of given test data(test.csv)


