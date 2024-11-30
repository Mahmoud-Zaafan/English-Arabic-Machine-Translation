# English-Arabic Machine Translation

## Overview
This project involves developing a neural machine translation system for English-to-Arabic translations using deep learning techniques. It features a custom Transformer model for efficient and accurate language translation.

## Project Structure
- `notebooks/`: Contains the main Jupyter Notebook (`English-Arabic-Machine-Translation.ipynb`) used for model training and evaluation.
- `data/`: Includes the datasets used for training and testing the model.

## Dataset
- Processed 17,319 bilingual sentence pairs from an original dataset of 37,051 pairs.
- Removed duplicates and short sentences (<5 words).
- Addressed vocabulary sparsity:
  - English vocabulary size: 15,381 words.
  - Arabic vocabulary size: 35,033 words.

## Model Details
- **Baseline Models**: LSTM and GRU were tested but underperformed.
- **Transformer Model**:
  - Custom architecture with positional embeddings and multi-head attention.
  - Hyperparameters: 512 units, 4 layers, 8 attention heads.
  - Achieved 99.5% validation accuracy.

## Features
- Robust pipeline for real-time, unseen translations.
- Preprocessing steps include tokenization and vocabulary optimization.

## Technologies Used
- Python
- TensorFlow, TensorFlow Text, Keras
- NumPy, Pandas, Scikit-learn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/English-Arabic-Machine-Translation.git
