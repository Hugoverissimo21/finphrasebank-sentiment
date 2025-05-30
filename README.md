# CAA02

Project 

## Data

### Data Source

https://huggingface.co/datasets/takala/financial_phrasebank

which contains 50agree, 66agree, 75agree, allagree: all inside `data/FinancialPhraseBank-v1.0`

### Data TO BE USED

for **test** `data/75Agree_test.csv` should **ALWAYS** be used, its our benchmark

for **train** you can either use `data/75Agree_train.csv` OR `data/AnyAgree_train.csv`. 75Agree_train.csv contains the *normal* train set, while AnyAgree_train.csv contains the *extended* train set, so you can atribute weights based on agreement level