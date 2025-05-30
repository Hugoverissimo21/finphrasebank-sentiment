# CAA02

Project 

## Data

### Data Source

https://huggingface.co/datasets/takala/financial_phrasebank

which contains 50agree, 66agree, 75agree, allagree: all inside `data/FinancialPhraseBank-v1.0`

### Data TO BE USED

for **test** `data/75Agree_test.csv` should **ALWAYS** be used, its our benchmark

for **train** you can either use `data/75Agree_train.csv` OR `data/AnyAgree_train.csv`. 75Agree_train.csv contains the *normal* train set, while AnyAgree_train.csv contains the *extended* train set, so you can atribute weights based on agreement level

## Models

1. Base Model

    - Train and Test: 75Agree_train.csv and 75Agree_test.csv
    - Data balance
    - Some model
    - lalla

2. Data Augmentation Model

    - Train and Test: 75Agree_train.csv and 75Agree_test.csv
    - Data balance
    - Some model
    - **Use data augmentation** techniques such as back-translation, synonym replacement, etc.
    - https://neptune.ai/blog/data-augmentation-nlp
    - lalla

3. Weights Model

    - Train and Test: AnyAgree_train.csv and 75Agree_test.csv
    - Data balance
    - Some model
    - **Use weights based on agreement level** (50agree, 66agree, 75agree, allagree)
    - lalla

4. ... ?!?!?!

    - ?!?!?!