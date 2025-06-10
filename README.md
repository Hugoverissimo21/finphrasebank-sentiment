# Sentiment Classification of Financial Texts

- Hugo Veríssimo

- João Cardoso

## Abstract

This work explores financial sentiment analysis using the Financial PhraseBank dataset, a benchmark in the field for its annotated financial news snippets. The performance of three different models, fastText, LSTM, and BERT, is evaluated and compared on a selected subset with 75\% annotator agreement. BERT-based models significantly outperform the others, motivating further refinement through data augmentation and a novel weighted training strategy that incorporates annotator agreement levels during training. The proposed models achieve performance in line with, or surpassing, literature baselines, demonstrating the importance of both architecture selection and annotation-informed weighting schemes in financial NLP.

## Data Source

[Financial PhraseBank](https://huggingface.co/datasets/takala/financial_phrasebank)

## Files Description

- `assets/` - contains the assets used in the project, such as figures

- `data/` - contains the FinancialPhraseBank dataset and train/test split

- `report/` - contains the report latex files

- `data EDA.ipynb` - contains the exploratory data analysis of the dataset

- `model *.ipynb` - contains the model training and evaluation code

- `model *.csv` - contains the model cross-validation results

- `results.ipynb` - contains the comparison of the models