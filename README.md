# NLP-Skip-Gram-Model-for-Word-Embeddings-A-Python-Implementation
Skip-Gram Model word2vec Example - Discover how to apply the skip-gram algorithm in NLP to create word embeddings from a document dataset.

Project Root/
- Input/
  - config.py          : Configuration file for setting parameters
  - Engine.py          : Main engine logic for training the model
  - complaints.csv     : Input dataset for word embeddings

- Output/
  - emb.pkl            : Saved word embeddings
  - idx2word.pkl       : Mapping of indices to words
  - tokens.pkl         : Tokenized words from the input data
  - weights.pkl        : Model weights
  - word2idx.pkl       : Mapping of words to indices

- Source/
  - __pycache__/       : Python bytecode cache
  - data.py            : Script for data preprocessing and handling
  - model.py           : Script defining the skip-gram model
  - utils.py           : Utility functions for model support

- processing.py        : Data processing script
- README.md            : Documentation for the project
- requirements.txt     : Required Python libraries for the project
- skip_gram.ipynb      : Jupyter notebook for running and experimenting with the skip-gram model
