

# 🧠 Natural Language Processing (NLP) – Preprocessing & Text Representation

This project focuses on building **foundational NLP preprocessing and text representation pipelines** using Python, with the goal of transforming raw text into machine-learning-ready numerical features.

The implementation emphasizes understanding how different preprocessing choices and vectorization techniques influence feature quality and representation behavior.

---

## 📌 Tools & Libraries

* Python
* NLTK
* scikit-learn
* Gensim
* NumPy / Pandas

---

## ⚙️ Implementation Work

* **Text Cleaning (Regex)**
  Removed punctuation, special characters, and unwanted symbols.

* **Tokenization**
  Split text into sentence-level, word-level, character-level, and punctuation-level tokens.

* **Stopword Removal**
  Eliminated high-frequency non-informative words.

* **Stemming (Porter, Regex Stemmer)**
  Reduced words to root forms using rule-based truncation.

* **Lemmatization**
  Converted words to dictionary base form using linguistic context.

* **Part-of-Speech (POS) Tagging**
  Assigned grammatical roles (noun, verb, adjective, etc.) to words.

---

## 🔢 Text Representation Techniques

* **One-hot Encoding**
  Binary vector representation of vocabulary.

* **Bag of Words (BoW)**
  Frequency-based word count vectors.

* **TF-IDF (Term Frequency – Inverse Document Frequency)**
  Weighted word importance representation.

* **Word2Vec – CBOW**
  Predicts target word from surrounding context.

* **Word2Vec – Skip-gram**
  Predicts surrounding context from target word.

---

## 🔍 Explorations

* Compared sparse count-based vectors vs dense embedding-based vectors.
* Studied effect of preprocessing steps on vocabulary size and sparsity.
* Visualized word frequency distributions.
* Generated and inspected word embedding vectors.

---

## ✅ Key Takeaways

* Preprocessing choices strongly influence feature quality.
* TF-IDF provides better discrimination than raw counts.
* Word embeddings capture semantic similarity better than BoW/TF-IDF.
* No single representation works best for all NLP tasks.

---
