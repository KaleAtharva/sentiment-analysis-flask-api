
# Sentiment Analysis Flask API

# About

This is a flask API for the restaurant review sentiment analysis model.

# Working

1. Loading the model and tfidf vectorizer:
Using the load class of joblib library the classification model and tfidf vectorizer is loaded.

2. Text Preprocessing function:
This function takes a text and cleans it and returns a text free from punctuations ,stopwords and which is stemmed using porter stemmer.

3. Predict function:
This function recieves the input text after hitting the submit button on browser i.e. it acts as an API endpoint where the endpoint location is /predict.
It recieves a request in form of json object and returns predicted value to the web browser in the form of json.




## Dependencies

1. Flask
```bash
  pip install Flask
```

2. Joblib
```bash
  pip install joblib
```

3. NLTK
```bash
  pip install nltk
```

4. Scikit Learn
```bash
  pip install scikit-learn
```

5. Flask CORS
```bash
  pip install flask-cors
```
## Run Locally

Clone the project

```bash
  git clone https://github.com/KaleAtharva/sentiment-analysis-flask-api.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

Run Python File

```bash
  python3 filename.py
```





## Authors

- [@Atharva Kale](https://github.com/KaleAtharva)

