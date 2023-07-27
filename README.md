# Sentiment-Analysis-using-Natural-Lanuage-Processing
It is a NLP based project, which is built to analyze the sentiment of the product review, weather it is positive, negative or neutral.

In this project, we will go through a Natural Language Processing Python Project creating a Sentiment Analysis classifier with NLTK's VADER and Huggingface Roberta Transformers. 

The project is to classify the seniment of amazon customer reviews. Which are nothing but the product reviews of people, on what they think about the product they bought, is it good, is it bad or they have a mixed reaction about that product.

So, the first thing done in the project is to import the data and libraries like pandas, numpy matplotlib and seaborn, and the natural language toolkit('NLTK')

Then import the dataset which is in the form of '.csv' file and perform EDA on it.

In the next step VADER i.e ( Valence Aware Dictionary for Sentiment Reasoning) is used, VADER is an NLTK module that provides sentiment scores based on the words used. In this step SentimentIntensityAnalyzer is also used to get neg/neu/pos scores of the text.

After the VADER scores gets determined, now we plot that to get a better visualization of the compound scores on the basis of stars ratings using seaborn.

After plotting the graph, in the next step RoBERTa model is used, RoBERTa (Robustly Optimized BERT-Pretraining Approach) model is a pretrained model which is used for pretraining natural language processing (NLP) systems that improve on Bidirectional Encoder Representations from Transformers (BERT).

Then, we apply tokenizers imported from transformers and calculate the polarity scores.

After that compare the scores of both the models, RoBERTa and VADER and plot them using seaborn.

And after that in the final step, we use pipeline for the deal model.

And finally, our model is successfully created, and is ready to analyze the sentiment of the reviews, given as inputs weather they are positive, negative or neutral.

