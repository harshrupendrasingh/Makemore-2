# Makemore-2
This Colab notebook implements a character-level language model in PyTorch. It reads a names.txt dataset, builds a vocabulary, and trains a neural network to predict the next character in a sequence. The notebook includes data preprocessing, model training, and generating new names, with visualizations of character embeddings.
Character-Level Language Model with PyTorch
This repository contains a Colab notebook that implements a character-level language model using PyTorch. The model is trained to predict the next character in a sequence based on a dataset of names, enabling the generation of new names.

Character-Level Language Model with PyTorch
This repository contains a Colab notebook that implements a character-level language model using PyTorch. The model is trained to predict the next character in a sequence based on a dataset of names, enabling the generation of new names.

Overview
The notebook demonstrates the following steps:

Data Preprocessing: Converts a dataset of names (names.txt) into a format suitable for training, building a vocabulary of characters, and mapping them to/from integer indices.
Model Architecture: Uses a simple neural network with embeddings and fully connected layers to model the sequence of characters.
Training: Trains the model using a cross-entropy loss function and tracks the training loss.
Generation: Generates new names by sampling from the trained model.
Visualization: Includes visualizations of the learned character embeddings using Matplotlib.
Getting Started
Prerequisites
Google Colab account
Basic understanding of PyTorch

Usage
Preprocessing: The notebook reads the names.txt file, builds the dataset, and splits it into training, validation, and test sets.
Training: The model is trained with a context size of 3 characters. Training progress is visualized through loss plots.
Generation: After training, the model can generate new names by sampling characters one at a time.
Visualization: Visualize the learned character embeddings to see how the model clusters similar characters.
