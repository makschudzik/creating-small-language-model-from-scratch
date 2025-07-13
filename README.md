# Creating a Small Language Model from Scratch

This project implements a simple, neural network-based Language Model entirely from scratch using the PyTorch library. It's designed to demonstrate fundamental concepts in Natural Language Processing (NLP) and deep learning mechanisms, providing a clear and hands-on learning experience.

## 🚀 Project Overview

This notebook covers the following steps:
1.  **Text Data Preparation** - Loading and preprocessing text data, including tokenization and vocabulary building.
2.  **Dataset Creation** - Building context-next word pairs for language model training.
3.  **Neural Network Model Definition** - Construction of a simple neural network architecture, including an embedding layer.
4.  **Training Loop Implementation** - Detailed illustration of the training process, loss function (Cross-Entropy Loss), and weight updates via backpropagation.
5.  **Model Evaluation** - Using perplexity as a metric to evaluate the quality of the language model.
6.  **Word Embeddings Visualization** - Demonstrating how the model learns meaningful representations of words in a vector space.

## 📊 Results

Initial analysis shows that even a simple model built from scratch can learn meaningful word representations. While trained on a small dataset and limited iterations, the project successfully demonstrates the core mechanics of a neural network-based language model. This highlights a foundational understanding crucial for more complex NLP tasks.

## 🗂️ Dataset

The dataset used in this project is a simple text file named `sentences.txt`, which should contain a collection of sentences.

Please place the `sentences.txt` file in the root directory of this repository before running the notebook.

## 🔧 Installation

To set up this project locally, clone the repository and install the required dependencies:

```bash
git clone [https://github.com/makschudzik/Creating-Small-Language-Model-from-Scratch.git](https://github.com/makschudzik/Creating-Small-Language-Model-from-Scratch.git) # Adjust if your repo name is different
cd Creating-Small-Language-Model-from-Scratch
pip install -r requirements.txt
