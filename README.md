# Sentiment Analysis Project 📊💬 (Amazon Reviews)

This project performs **Sentiment Analysis** on text data (especially **Amazon product reviews**) using:
- **VADER Sentiment Analyzer** (Lexicon + rule-based sentiment analysis)
- **RoBERTa (Transformers)** model: `cardiffnlp/twitter-roberta-base-sentiment`

The goal is to classify reviews into **Positive / Negative / Neutral** sentiment and compare the performance of both approaches.

---

## 🚀 Features
- Sentiment analysis using **VADER**
- Sentiment prediction using **HuggingFace Transformers (RoBERTa)**
- Probability scores using `softmax`
- Works well for **Amazon reviews / product feedback / social media text**
- Comparison between **rule-based** and **deep learning-based** sentiment methods

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Transformers (HuggingFace)
- SciPy
- VADER Sentiment
- Pandas / NumPy

---


---

## 📌 Dataset
This project can be used on **Amazon Product Reviews Dataset**, where users leave feedback about products.
Example review text:
- "The product quality is amazing!"
- "Worst purchase ever, totally disappointed."
- "It’s okay, not great but not bad."

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/sentiment-analysis-project.git
cd sentiment-analysis-project

