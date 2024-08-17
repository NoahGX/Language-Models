# Language Models

## Overview
The purpose of this Jupyter Notebook is to demonstrate the creation and evaluation of a basic trigram language model. It includes sections for installing necessary libraries, preprocessing text data, training the model, and calculating its statistical measure of how well a probability model predicts a sample.

## Features
- **Trigram Language Model:** Constructs a language model based on trigrams extracted from a text corpus.
- **Perplexity Calculation:** Includes functionality to compute the language model, providing quantitative measure of the model's performance.

## Usage
- Run the cells sequentially from top to bottom.
- Train the model using provided or custom text data.
- Execute the calculation cells to assess how well the language model predicts new text data.

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: `numpy`, `gzip`, `cytoolz`, `collections`, `pytest`, `ipytest`

## Input
The model requires a corpus of text data formatted as a list of sentences for training and evaluation.

## Output
- Outputs the constructed trigram language model.
- Provides a score indicating the predictive performance of the model on a given text corpus.

## Notes
- Ensure all dependencies are installed correctly.
- The notebook includes tests that can be run to ensure the functions are working as expected.