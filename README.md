# Emotion Classification Using Transformers

This project implements an emotion classification model using the `distilbert-base-uncased` model and the `dair-ai/emotion` dataset. The model is fine-tuned to classify emotions in text data, achieving a high level of accuracy and F1 score on the test set.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Emotion classification is a crucial task in natural language processing (NLP) that involves identifying the emotional tone behind a piece of text. This project uses a transformer-based model, `distilbert-base-uncased`, to classify text data into different emotion categories.

## Dataset

The `dair-ai/emotion` dataset is used for training and evaluating the model. This dataset contains text samples labeled with one of several emotion categories.

## Model

The model used is `distilbert-base-uncased`, a distilled version of BERT (Bidirectional Encoder Representations from Transformers). DistilBERT retains 97% of BERT's language understanding while being faster and smaller.

## Results

The model achieves the following performance on the test set:

- **Test Accuracy:** 92.15%
- **Test F1 Score:** 0.9212

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the necessary dependencies using the following command:

```bash
pip install transformers accelerate datasets scikit-learn
