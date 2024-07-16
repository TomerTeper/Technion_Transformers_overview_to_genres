
# Multi-Label Classification for Movie Genres

This project demonstrates a multi-label classification approach using the Hugging Face Transformers library to predict movie genres based on their overviews.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Installation

First, ensure you have Python and pip installed. Then, install the required libraries:

\`\`\`bash
pip install datasets transformers pandas numpy scikit-learn matplotlib seaborn
\`\`\`

## Dataset

The dataset used in this project is assumed to be a TSV file containing movie data. The file should be named \`the_movie_database_data.tsv\` and located in the current directory.

## Data Preparation

The data preparation steps involve reading the dataset, extracting relevant information, and converting nested JSON columns into a suitable format for model training.

## Model Training

The model used is a transformer model from the Hugging Face library. The data is tokenized and then split into training and evaluation sets.

## Evaluation

The model is evaluated on a test set using several metrics, including F1 score, Hamming loss, and exact match.

## Results

The results of the model evaluation are printed out after training and evaluation steps. You can visualize these results and adjust your model parameters accordingly.

## Acknowledgements

This project uses the Hugging Face Transformers library and the datasets library for model training and evaluation.
