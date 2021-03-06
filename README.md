# Abstractive-Text-Summarization

# NLP Best Practices
In recent years, natural language processing (NLP) has seen quick growth in quality and usability, and this has helped to drive business adoption of artificial intelligence (AI) solutions. In the last few years, researchers have been applying newer deep learning methods to NLP. Data scientists started moving from traditional methods to state-of-the-art (SOTA) deep neural network (DNN) algorithms which use language models pretrained on large text corpora.

This repository contains Extractive Text Summarization using Bert and Abstractive Text Summarization using T5, provided as Jupyter notebooks and utility functions. The focus of the repository is on state-of-the-art methods and common scenarios that are popular among researchers and practitioners working on problems involving text and language.

# Target Audience
For this repository our target audience includes machine learning enthusiasts with varying levels of NLP knowledge as our content is source-only and targets custom machine learning modelling. The utilities and examples provided are intended to be solution accelerators for real-world NLP problems.

# Content
The following is a summary of the commonly used NLP scenarios covered in the repository. Each scenario is demonstrated in one or more Jupyter notebook examples that make use of the core code base of models and repository utilities.

Text summarization is a language generation task of summarizing the input text into a shorter paragraph of text.

# Install
This project requires Python 3.6 and the following Python libraries installed:

-  NumPy
-  Pandas
-  Torchtext
-  Transformers
-  py-rouge
-  PyTorch
-  sentencepiece

# Dataset 
The dataset we used for this notebook is CNN/DM dataset which contains the documents and accompanying questions from the news articles of CNN and Daily mail. The highlights in each article are used as summary. The dataset consits of ~289K training examples, ~11K valiation examples and ~11K test examples.

# Models Used
-  Bert

   This notebook demonstrates how to fine tune Bert Classifier for extractive text summarization. Utility functions and classes in the NLP Best        Practices repo are used to facilitate data preprocessing, model training, model scoring, result postprocessing, and model evaluation.
-  T5

   This notebook demonstrates how to use huggingface’s transformers library to summarize any given text. T5 is an abstractive summarization            algorithm.
# Rouge Scores

| Model | ROUGE-1 | ROUGE-2 | ROUGE-L |
| ------------- | ------------- | ------------- | ------------- |
| BERT-extractive (BERT+CLASSIFIER)  | 37.95  | 15.67  | 34.40  |
| Hybrid BERT +T5  | 32.94  | 11.18  | 26.28  |

   
  
# STEPS:
-  Execute Bert for Extractive Summarization
-  Execute T5 for Abstractive Summarization
-  Calculate Rouge score
 
 
# SUBMITTED BY:
-  Anita Choudhary
-  Srishti Srivastava
-  Prateek Sharma
