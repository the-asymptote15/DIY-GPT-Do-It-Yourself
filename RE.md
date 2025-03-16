# 🚀 From Bi-grams to GPT: A Journey in Language Modeling

Welcome to **From Bi-grams to GPT**, a repository that explores the evolution of language models—starting from a simple statistical bigram model and progressing to a fully functional GPT-style transformer model, all implemented from scratch in PyTorch!  

## 📂 Project Structure  


## 🧠 What's Inside?  

### 1️⃣ **Bigram Model (`statistical_bigram.py`)**  
🔹 A simple statistical approach where the next token is predicted based on the previous one.  
🔹 Uses an embedding table where each token learns its next-token probabilities.  
🔹 Quick to train but lacks deep contextual understanding.  

### 2️⃣ **GPT-like Transformer (`gpt.py`)**  
🚀 A modern language model with:  
✔ Multi-head self-attention for context awareness  
✔ Position embeddings to capture sequential order  
✔ Transformer blocks with layer normalization and dropout  
✔ Token generation using learned probabilities  

## 🔧 Setup  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name

2. **Install dependencies**  

pip install torch


3. **Train and Run the Models**  

python statistical_bigram.py

