# MSc Business Analytics Consultancy Project/Dissertation 2019-20
## All codes have been uploaded onto this "dissertaion" repository
## Datasets can be downloaded from: https://drive.google.com/drive/folders/1uMjO6oXWfTbbd7_sRDELSmZi_i2aARh9?usp=sharing)
## We should run the notebooks in the following order:
#### 1. yelp_random_sample.ipynb 
(This notebook is about converting json to csv. It's optional, can start from the 2nd notebook. The original Yelp Datasets can be accessed from: https://www.yelp.com/dataset)
#### 2. Final EDA.ipynb
(This notebook contains the full exploratory analysis of the five datasets)
#### 3. Sentiment_Preprocessing.ipynb
(sentiment preprocessing before modelling)
#### 4. Topic Modelling
(Build a LDA topic model for Tips)
#### 5. TEXT_ONLY_MODELS
(ML Models that only include text-based features)
#### 6. HYBRID MODELS.ipynb
(ML Models that contain both text-based and numerical features)
#### 7. Hyperparameter_tuning.ipynb
(Hyperameter tuning the final model)
#### 8.NEURAL NETWORKS.ipynb
(need to download Fast Text word vectors "wiki-news-300d-1M.vec",https://fasttext.cc/docs/en/english-vectors.html)

## The following packages might need to be installed before running the notebooks:
#### 1.	XGBoost: pip install xgboost
#### 2.	Keras: pip install Keras
#### 3.	Tensorflow: pip install --upgrade tensorflow
#### 4.	Genism: conda install -c conda-forge genism
#### 5.	Textblob: conda install -c conda-forge textblob
#### 6.	stop-words: pip install stop-words
#### 7.	pyLDAvis: conda install -c conda-forge pyldavis
#### 8.	chart_studio: pip install chart_studio
#### 9.	spaCy: conda install -c conda-forge spacy, python -m spacy download en
#### 10.	WordCloud: conda install -c conda-forge wordcloud=1.6.0
