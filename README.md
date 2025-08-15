#      Evaluating Historical Language Models for literary research
This repository contains the research done as part of my thesis.

# Structure

- the data folder contains all the used data:
  files for the token-level experiments:
  eng-danc.json
  eng-fina.json
  eng-houn.json
  eng-nava.json
  eng-redh.json
  eng-scan.json
  eng-spec.json
  file for the sentence-level experiments:
  speckled-band-chunk-sentiment.json
  and the modern benchmark:
  test_benchmark.csv
  train_benchmark.csv

- the token-level experiment is contained in the folder by the same name inside there are:
    notebooks that explore the data: BERT-explore, BERT-explore2, BERT-token_positive, neutral_interval, token_level_exploration
    notebooks with BERT doing sentiment analysis: BERT-token_system and BERT-token_system-seeds
    notebooks with TuringBERT doing sentiment analysis: TuringBERT-token_system and TuringBERT-token_system-seeds
    files with results (the csv files)

- the sentence-level experiment is contained in the folder by the same name inside there are:
    notebooks with BERT doing sentiment analysis on the modern benchmark: BERT-benchmark and BERT-benchmark-seeds
    notebooks with BERT doing sentiment analysis on the historical benchmark: 10cross_BERT_sentence_level and 10cross_BERT_sentence_level-seeds
    notebooks with TuringBERT doing sentiment analysis on the modern benchmark: TuringBERT-benchmark and TuringBERT-benchmark-seeds
    notebooks with TuringBERT doing sentiment analysis on the historical benchmark: 10cross_TuringBERT_sentence_level and 10cross_TuringBERT_sentence_level-seeds
    files with results (the tsv files)
  
- the thesis report

Running the code might require importing some common packages, they are all mentioned in the begging of each notebook.

You must have the BERT model and a TuringBERT model downloaded.







