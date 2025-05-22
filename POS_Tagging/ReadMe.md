# POS Tagging with Recurrent Neural Networks

This project addresses **Part-of-Speech (POS) tagging** using **recurrent neural architectures** such as LSTM and GRU-based models.

## Objective

The goal is to build a neural sequence labeling model capable of accurately assigning POS tags to words in a sentence, leveraging the sequential context via recurrent neural networks.

## Dataset

The project uses the [NLTK Dependency Treebank](https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/dependency_treebank.zip), which contains syntactically annotated sentences suitable for POS tagging tasks.

📂 **Download Dataset**:  
[https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/dependency_treebank.zip](https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/dependency_treebank.zip)

## Methodology

- **Preprocessing:** Sentences and tags are extracted from the dependency treebank corpus and tokenized appropriately.
- **Model Architecture:** Recurrent neural network models, such as:
  - Simple RNN
  - LSTM
  - Bidirectional LSTM
- **Embedding:** Word embeddings (e.g., pretrained or learned) are used as input features.
- **Training Objective:** The model is trained to minimize cross-entropy loss between predicted and true POS tags for each token.

## Future Improvements

- Add character-level embeddings to handle out-of-vocabulary words
- Experiment with CRF (Conditional Random Fields) on top of RNN outputs
- Integrate attention mechanisms
- Compare with transformer-based baselines (e.g., BERT for POS tagging)

