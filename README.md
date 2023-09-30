# README

This repository comprises three distinct projects, each residing in its designated folder. Below, we provide detailed information on each project, along with crucial details for understanding, executing, and replicating the outcomes.

## Project 1: Cryptography - Caesar Cipher RNN Model

### Folder: `caesar_cipher`

**Description:**
This project focuses on encrypting English text using the Caesar cipher and subsequently training a Recurrent Neural Network (RNN) model to decipher the encrypted text. The model is trained on an English dataset and demonstrates its effectiveness in decrypting Caesar cipher-encrypted sentences through a character-level RNN architecture.

**Key Components:**
- `Caesar_cipher.ipynb`: A Jupyter notebook that covers the entire implementation, including data preprocessing, model creation, training, and evaluation.
- `data/eng-nld/eng-nld.txt`: The dataset used for training the model contains English sentences.

**How to Run:**
1. Open and run the `caesar_cipher.ipynb` notebook in a Jupyter environment.
2. Ensure that the required libraries are installed (`torch`, `sklearn`, `nltk`).
3. Follow the instructions in the notebook to train the model and evaluate its performance.

**Results:**
The model achieves an impressive accuracy (BLEU score of 100%) on the test set, showcasing its proficiency in decrypting Caesar cipher-encrypted English sentences.

---

## Project 2: Sequence Prediction - RNN, GRU, LSTM Models

### Folder: `predictor`

**Description:**
This project explores sequence prediction using various recurrent neural network (RNN) architectures, including RNN, GRU, and LSTM cells. The models are trained to predict the cumulative sum of randomly generated integer sequences.

**Key Components:**
- `predictor.ipynb`: A Jupyter notebook covering the entire implementation, from data generation to model creation, training, and evaluation.

**How to Run:**
1. Open and run the `predictor.ipb` notebook in a Jupyter environment.
2. Ensure that the required libraries are installed (`torch`).
3. Follow the instructions in the notebook to train the models and evaluate their performance.

**Results:**
All models (RNN, GRU, LSTM) achieve 100% accuracy on the validation set, demonstrating their capability to predict cumulative sums of sequences.

---

## Project 3: Machine Translation - English to Dutch Language

### Folder: `morse_code_translation`

**Description:**
This project involves building a machine translation model to convert English sentences to Dutch (NLD) language. The model is implemented using a sequence-to-sequence architecture with attention mechanisms.

**Key Components:**
- `translator.ipynb`: A Jupyter notebook containing the entire implementation, covering data preprocessing, model creation, training, and evaluation.
- `data/eng-nld/eng-nld.txt`: The dataset used for training the model contains English sentences.


**How to Run:**
1. Open and run the `morse_code_translation.ipb` notebook in a Jupyter environment.
2. Ensure that the required libraries are installed (`torch`).
3. Follow the instructions in the notebook to train the model and evaluate its performance.

**Results:**
The machine translation model successfully translates English sentences into Dutch, demonstrating high accuracy in the translation task.

---

## General Notes:

- Each project folder contains a dedicated Jupyter notebook providing a comprehensive overview of the entire workflow, facilitating understanding and replication of results.
- Ensure that the necessary libraries and dependencies are installed before executing the notebooks.
- Experiment with hyperparameters, data, and model architectures to further explore and enhance the performance of the models.
