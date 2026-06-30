# 📝 Next Word Prediction using LSTM

This project implements a **Next Word Prediction** model using **Long Short-Term Memory (LSTM)** networks. The model is trained on *The Adventures of Sherlock Holmes* by Arthur Conan Doyle and learns language patterns to predict the next word in a given text sequence.

## 🚀 Project Highlights

* Built a deep learning model using **TensorFlow/Keras**.
* Trained on the complete text of *The Adventures of Sherlock Holmes*.
* Performed text preprocessing, tokenization, sequence generation, and padding.
* Used an **Embedding Layer**, **LSTM (150 units)**, and a **Softmax output layer** for next-word prediction.
* Generated coherent text by predicting words iteratively from a user-provided seed sentence.

## 🧠 Model Architecture

* **Embedding Layer** (100-dimensional word embeddings)
* **LSTM Layer** (150 units)
* **Dense Output Layer** with Softmax activation
* **Optimizer:** Adam
* **Loss Function:** Categorical Cross-Entropy

## 📊 Results

* Vocabulary Size: **8,200 words**
* Final Training Accuracy: **75.91%**
* Validation Accuracy: **26.86%**
* Model Perplexity: **2.90**

The model successfully learned contextual relationships between words and generated meaningful sentence continuations. Although the validation accuracy indicates some overfitting, the model demonstrates the effectiveness of LSTMs for sequence prediction tasks.

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Scikit-learn
* Jupyter Notebook

