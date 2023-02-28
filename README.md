# NLP-4-Hate-Speech-Recognition

## Problem definition:

Hate speech on social media has become a pervasive issue in recent years, causing harm to individuals and communities by perpetuating discriminatory attitudes and even sometimes inciting violence. As such, the ability to **detect and classify hate speech** in social media is critical in order to confront it.

## Objective and success metrics:

The objective of this NLP project is to develop the skills necessary to build a model that can effectively detect and classify hate speech in social media, specifically using unstructured data – in this case, labeled Tweets. To achieve this, we will use **NLP transformer models to preprocess and tokenize the tweets, applying then various supervised machine learning algorithms** to analyze the text and classify it as either hate speech or not.

To evaluate the results, we will be using **F1-score on positive cases as success metric**, aiming to obtain a result **equal or above 0.65**


## Challenges detected:
* **Transform unstructured data into processable inputs:** Text by itself is not a valid numeric input that can be used in ML models.

* **Understand the text beyond just formal language rules:** The language used on social media is filled with slang and expressions that communicate based on context, making it difficult to process the data with ML models.

* **Unbalanced dataset:** Just **7.01%** of the cases provided in the dataset are positive for hate speech.


## Data for the project:

The data used for this project is retrived from [Kaggle](https://www.kaggle.com/code/helayahyaoui/nlp-twitter-sentiment-analysis/data?select=train.csv) and consists of a CSV file containing **29,530** tweets with the following variables:
* *id:* (numeric) Tweet ID
* *label:* (dummy) Tweets that are positive for hate speech are marked with 1, while those that are not are marked with 0.
* *tweet:* (text) Raw text from the retrived tweets.
