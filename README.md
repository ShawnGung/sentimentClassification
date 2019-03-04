# sentimentClassification

This repository is about our NLP coursework(the OffensEval 2019 challenge, details can be found [here](https://competitions.codalab.org/competitions/20011)).

Our approach involves the use of the pretrained Glove Vector word embeddings, and then apply textCNN as classifier. Because of the imbalance dataset, we grid search the threshold of the logistic regression for minimise the impace of imbalance data.

The full report can be found in the [Report.pdf](./report.pdf) file.
