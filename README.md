# 🧹 Text Data Cleaning Pipeline for NLP

This project demonstrates how to clean and preprocess raw text data using Python. It is a foundational step for any Natural Language Processing (NLP) task such as sentiment analysis, chatbots, document classification, etc.

---

## 🎯 Objective

To create a reusable text preprocessing pipeline that:
- Removes URLs, hashtags, mentions, digits, and special characters
- Converts text to lowercase
- Removes stopwords
- Tokenizes and lemmatizes words

---

## 🗂️ Dataset

In this project, we use a few sample text strings to demonstrate the pipeline. However, the pipeline is scalable and can be applied to any text dataset like:
- Movie reviews (IMDb)
- Twitter data
- News articles
- Custom datasets

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Regular Expressions (`re`)
- [NLTK (Natural Language Toolkit)](https://www.nltk.org/) for:
  - Tokenization
  - Stopwords
  - Lemmatization

---

## 🧪 Sample Texts Processed

```text
Original: "Hello!!! This is a test tweet... #AI @OpenAI"
Cleaned:  "hello test tweet"

Original: "Preprocessing is FUN 😄🔥🔥"
Cleaned:  "preprocessing fun"
