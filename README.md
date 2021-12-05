# credit-default-prediction

## Quickstart

```
conda create -n loan python=3.9  
conda activate loan
pip install -r requirements.txt
jupyter lab prediction.ipynb 
```
Download the data from https://www.kaggle.com/dopicardo/loan-data and move in `./Loan Data`


## Introduction

A financial institution is looking for a better approach to
identify credit defaulters. They would like to understand if it's
possible to predict which customers are likely to default on their loan
payments after receiving their loan approval. If not possible then our
client is interested to understand what is required to enable this in
the future and thus resolve the obstacle.

## Data

There are three datasets:

- *Borrower Information*: Information on the clients' customers

- *Loan Classification Information*: Information on the loan itself

- *Loan Payment Information*: Information on the payments on the
    loans.

As well as a data dictionary *"Feature Explanations.csv"*

## Deliverables

- [Python notebook](prediction.ipynb)
- [Presentation](doc/presentation.pdf)
