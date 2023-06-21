# rusentne-2023-prompt-tuning
Prompt-tuning approach to targeted sentiment analysis on Russian news dataset 

This repo contains prompt learning implementation of named entity oriented sentiment analysis, described in the paper Prompting Question Answering Models for Targeted Sentiment Analysis. The OpenPrompt package was used to conduct the experiments (https://github.com/thunlp/OpenPrompt).

--------
## Dataset
The **dataset** directory contains two subfolders:
- *cross validation splits*: 3-fold train/test splits to carry out cross validation
- *rusentne-2023 splits*: train, validation, and test sets provided by RuSentNE-2023 competition organizers
________
## Prompt learning experiments
The **notebook** directory contains the realization of prompt tuning experiments in the format of a Jupyter notebook. To average the results over several train/test splits, it is advised to use the *report_average* function. 
________
## Credits 
```
@article{Ding_OpenPrompt_An_Open-source_2021,
author = {Ding, Ning and Hu, Shengding and Zhao, Weilin and Chen, Yulin and Liu, Zhiyuan and Zheng, Hai-Tao and Sun, Maosong},
journal = {arXiv preprint arXiv:2111.01998},
title = {{OpenPrompt: An Open-source Framework for Prompt-learning}},
year = {2021}
}
```
