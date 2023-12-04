# EmailBasedPrediction
 Based on the content of the email, we aim to forecast whether the recipient is likely to engage by clicking on the provided link.

### Dataframe Formation
We possess a pickle (pkl) file encompassing unstructured email data, including fields such as 'subject,' 'body,' 'opened,' 'meeting link clicked,' and 'responded.' Our objective is to process this data and transform it into a structured dataframe.

### Data cleaning
The email subject and body contain emojis, I tried to remove them. Furthermore, we utilize NLP techniques such as stopword removal and stemming to preprocess the corpus.

### Data analysis
We employ pairplot visualization to explore the relationships between categorical variables and utilize a heatmap to assess dependencies among these variables.

### Feature engineering and NLP
We generate a novel feature by combining the subject and body of emails, forming a unified conversation. Additionally, we leverage natural language processing (NLP) techniques such as stemming, stopword removal, and employ both TF-IDF and CountVectorizer methods to gain insights from the conversation and create features based on its content.

### Model development
Chose Random Forest for modeling due to its robustness, resistance to overfitting, and suitability for handling diverse features from email data.

### Reporting
Achieved an 84% accuracy, which is commendable given the constraints of a small dataset.

<img width="331" alt="Screenshot 2023-12-04 173032" src="https://github.com/2809prashant/EmailBasedPrediction/assets/51948771/936f70de-336f-4c31-9fc0-9ff01cc8a069">
