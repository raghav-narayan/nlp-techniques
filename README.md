# 🧠 nlp-techniques  
**Py Notebooks that implement some of the NLP preprocessing techniques like TF-IDF, BoW etc. from scratch.**  
Custom implementation of a TF-IDF vectorizer from scratch along with max features functionality.

---

## 🚀 Features

- Custom implementation of **TF-IDF** with:
  - Term Frequency (TF)
  - Inverse Document Frequency (IDF) using scikit-learn's formula
- Alphabetically sorted vocabulary
- **L2-normalized** sparse matrix output
- Matching results with `sklearn.feature_extraction.text.TfidfVectorizer`
- **Max Features Option**: Keeps top 50 terms with highest IDF values
- Works with `.pkl` file-based corpora

---

## 📁 Project Structure

```bash
├── tfidf_vectorizer.ipynb      # Main notebook with implementation and comparison
├── cleaned_strings             # Pickle file (list of cleaned text strings) for Task-2
