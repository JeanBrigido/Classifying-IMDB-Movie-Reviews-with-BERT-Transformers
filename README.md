# Classifying IMDB Movie Reviews with BERT Transformers

This project implements text classification models to analyze and classify different aspects of IMDB movie reviews using both a simple neural network and a fine-tuned TinyBERT transformer model.

## Project Overview

The project focuses on classifying movie reviews into three aspects:
- Cinematography
- Characters
- Story

## Models Implemented

1. Simple Neural Network with Embedding Layer
2. Fine-tuned TinyBERT Transformer

## Requirements

- Python 3.x
- PyTorch
- Transformers (Hugging Face)
- Pandas
- NumPy
- Scikit-learn

## Project Structure

- `notebook.ipynb`: Main Jupyter notebook containing the implementation
- `datasets/`: Directory containing training and testing datasets
  - `imdb_movie_reviews_train.csv`
  - `imdb_movie_reviews_test.csv`

## Results

- Simple Neural Network: 68% accuracy
- Fine-tuned TinyBERT: 92% accuracy

## License

This project is licensed under the MIT License - see the LICENSE file for details.
