# Language_Translation_-seq-to-seq-
English-to-French Translation Model.

This project implements an English-to-French translation model using a sequence-to-sequence architecture with LSTM layers.
The model is trained on a dataset of English-French sentence pairs using Keras and TensorFlow.
The architecture includes an encoder to process the English input and a decoder to generate the French output, with one-hot encoded representations for both input and output sequences.

Features

- **Sequence-to-Sequence Model**: Uses LSTM-based encoder-decoder architecture for translation tasks.
- **One-Hot Encoding**: Represents English and French tokens using one-hot encoding for input and output sequences.
- **Inference Mode**: Supports real-time English sentence translation into French by decoding sequences one token at a time.
- **Validation Split**: During training, 20% of the data is used for validation to monitor model performance.
