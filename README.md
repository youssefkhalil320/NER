# Named Entity Recognition (NER) Model

This repository contains the implementation of a Named Entity Recognition (NER) model using both a BiLSTM and a BERT-based approach. The project demonstrates various aspects of NER, including data preprocessing, model training, and evaluation.

## Project Overview

The goal of this project is to build and evaluate NER models that can identify and classify named entities in text. The models implemented are:

1. **BiLSTM Model**: A traditional Bi-directional Long Short-Term Memory (BiLSTM) network with embedding layers for sequence labeling.
2. **BERT Model**: A modern BERT-based model for token classification to leverage pre-trained language representations.

## Installation

To get started, you need to install the required libraries. You can do this by running the following commands:

```bash
pip install tensorflow-addons
pip install transformers
pip install evaluate seqeval
