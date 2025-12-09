NLP Product Classification Project

This repository contains a semester project for product classification using NLP, where product descriptions are used to predict product categories.

Project Overview

Goal: Classify products into categories (e.g., Household, Books, Clothing & Accessories, Electronics) based on their textual descriptions.

Approach: Uses NLP techniques and deep learning models to analyze product descriptions and predict categories accurately.

Models Included:

BiLSTM for sequence modeling and classification.

DeBERTa-v3-small for transformer-based classification (requires Google Drive access due to large size).

Features

Predict categories from raw product descriptions.

Supports multiple deep learning architectures.

Ready-to-use inference notebooks for testing with new descriptions.

Files

.ipynb files – Jupyter notebooks containing model training and inference code.

Tokenizer and model files – Required for BiLSTM and DeBERTa inference (DeBERTa files are available via Google Drive).

Usage

Clone this repository:

git clone <repo-url>


Open the desired notebook in Jupyter or Google Colab.

Load the required model and tokenizer files.

Add new product descriptions and run the inference cells to predict categories.

Notes

DeBERTa-v3-small model cannot be uploaded due to size limitations; access it via Google Drive.

BiLSTM models are included and ready for direct use.
