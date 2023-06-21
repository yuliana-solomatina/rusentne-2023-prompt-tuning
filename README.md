# rusentne-2023-prompt-tuning
Prompt-tuning approach to targeted sentiment analysis on Russian news dataset 

This repo contains prompt learning implementation of named entity oriented sentiment analysis, described in the paper Prompting Question Answering Models for Targeted Sentiment Analysis.

--------
## Dataset
The **dataset** directory contains two subfolders:
- *cross validation splits*: 3-fold train/test splits to carry out cross validation
- *rusentne-2023 splits*: train, validation, and test sets provided by RuSentNE-2023 competition organizers
________
## Prompt learning experiments
The **notebook** directory contains the realization of prompt tuning experiments in the format of a Jupyter notebook. To average the results over several train/test splits, it is advised to use the *report_average* function. 
