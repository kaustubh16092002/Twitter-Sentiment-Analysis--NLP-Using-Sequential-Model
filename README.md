
# NLP based model to perform sentiment analysis on the corona virus tweets
A brief description of what this project does and who it's for


## Acknowledgements

 - [NLP:Twitter Sentiment Analysis](https://www.coursera.org/projects/twitter-sentiment-analysis)
 - [Dataset](https://www.kaggle.com/datatattle/covid-19-nlp-text-classification)
 - [Youtube](https://www.youtube.com/watch?v=ujId4ipkBio)

  
## Authors

- [@kaustubhmanitripathi](https://github.com/kaustubh16092002)

  
## Appendix

-Tanmay Vijay; Ayan Chawla; Balan Dhanka; Purnendu Karmakar
"Sentiment Analysis on COVID-19 Twitter Data"
Published in: 2020 5th IEEE International Conference on Recent Advances and Innovations in Engineering (ICRAIE)
DOI: 10.1109/ICRAIE51050.2020.9358301


  
## Documentation

Requirements:
There are some general library requirements for the project and some which are specific to individual methods

- numpy 
- pandas 
- Natural Language Toolkit  
- Beautiful Soap
- re,string,unicodedata
- keras.preprocessing  
- sklearn.metrics   classification_report,confusion_matrix,accuracy_score
- sklearn.model_selection   
- string,punctuation
- keras
- tensorflow 
- matplotlib 
- seaborn 
- tensorflow.keras.preprocessing.text   
- tensorflow.keras.preprocessing.sequence   

Preprocessing:
- Null value Removal
- EDA (Exploratory Data Analysis)
- merging the similar type of sentiments
- stopwords using nltk
- cleaning 
- assigning polarity to sentiments as 0, 1 and 2
- using tokenizer on training and testing
Training and Testing 
- Used sequential model for training and testing our dataset
- training the data using sequential model
Outcome:
- Accuracy, F1 score, precision, recall
