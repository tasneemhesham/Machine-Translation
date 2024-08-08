# English-to-Arabic Machine Translation

## Project Overview
This project focuses on developing a machine translation system for translating text from English to Arabic. The system utilizes advanced techniques, including LSTM (Long Short-Term Memory) networks and Transformer models, to achieve high-quality translations. Model performance is evaluated using BLEU (Bilingual Evaluation Understudy) metrics.

## Components

- **Dataset**: A large dataset containing English-Arabic sentence pairs is used for training and evaluation.
- **Data Cleaning**: The dataset undergoes several preprocessing steps:
  - **Lowercasing**: Converts all text to lowercase.
  - **Tokenization**: Splits text into tokens or words.
  - **Indexing**: Maps tokens to unique integer indices.
  - **Encoding**: Converts indexed tokens into embeddings.
  - **Padding**: Pads sequences to ensure uniform input size.

- **Model Architecture**:
  - **LSTM Model**: An LSTM network for capturing long-term dependencies in sequences.
  - **Transformer Model**: Utilizes the Transformer architecture for improved handling of sequential data with self-attention mechanisms.

## Implementation

### Data Preprocessing

1. **Lowercasing**: Normalize text to lowercase.
2. **Tokenization**: Break text into tokens.
3. **Indexing**: Create a vocabulary and convert tokens to integer indices.
4. **Encoding**: Convert indices into embeddings.
5. **Padding**: Ensure sequences have uniform length.

### Model Training

- **LSTM Model**:
  - Implemented using a sequence-to-sequence architecture with LSTM units.
  - Trained on the preprocessed dataset.

- **Transformer Model**:
  - Utilizes self-attention mechanisms for better performance.
  - Trained alongside the LSTM model to compare effectiveness.

### Transformer Implementation

For the Transformer model, we use the `transformers` library to leverage pre-trained translation models. Follow these steps to use the Transformer model:
