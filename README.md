# Next Word Predictor (RNN with PyTorch)

An implementation of a language modeling task that predicts the most probable next word in a sequence. This project utilizes **Recurrent Neural Networks (RNNs)** to capture temporal dependencies in text data, built entirely using the **PyTorch** framework.

O) 🚀 Overview
Language modeling is a fundamental task in Natural Language Processing (NLP). This project demonstrates how to preprocess a text corpus, build a character or word-level RNN architecture, and train it to generate coherent text by predicting subsequent tokens.


K) ✨ Key Features
* **Sequence Modeling:** Uses RNNs to maintain internal state and process sequences of varying lengths.
* **PyTorch Implementation:** Leverages `torch.nn` for model architecture and `torch.optim` for backpropagation through time (BPTT).
* **Text Preprocessing:** Includes tokenization, vocabulary mapping, and data loading pipelines.
* **Inference Engine:** A predictor function that takes a seed string and generates the next predicted word based on learned probability distributions.

P) 📁 Project Structure
* **`Predictor.ipynb`**: The primary Jupyter Notebook containing:
    * Data cleaning and normalization.
    * Embedding layer and RNN cell definitions.
    * The training loop with Loss/Accuracy monitoring.
    * Prediction logic for real-time testing.
* **`README.md`**: Comprehensive documentation of the project.

T) 🛠️ Tech Stack
* **Framework:** PyTorch
* **Language:** Python
* **Libraries:** NumPy, Matplotlib (for loss visualization)
* **Concepts:** RNNs, Embeddings, Cross-Entropy Loss, Softmax Activation.

### Prerequisites
You will need Python 3 and PyTorch installed:
```bash
pip install torch numpy
