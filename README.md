# 🚀 Spam Detection Using Advanced NLP Techniques

## 📊 Project Overview

This cutting-edge project leverages advanced Natural Language Processing (NLP) techniques to detect spam in email communications. We utilize an augmented version of the Enron public email corpus, specially curated for spam detection research.

---

## 📁 Dataset Details

| Attribute | Description |
|-----------|-------------|
| **Source** | Athens University of Economics and Business (AUEB) |
| **Ham Emails** | 3,672 |
| **Spam Emails** | 1,500 |

---

## 🛠 Methodology

### Text Processing and Tokenization
- 📚 NLTK for advanced tokenization and preprocessing
- 📊 Frequency distribution analysis for insight generation

### Feature Engineering
1. **Baseline Approach**: 
   - Bag-of-Words (BOW) / Unigram model
2. **Advanced Techniques**:
   - Stopwords filtering for noise reduction
   - Bigram features for context capture
   - Part-of-Speech (POS) tagging for linguistic insight

### Machine Learning Models
We employed a variety of models to ensure robust classification:

```python
models = [
    NaiveBayesClassifier(),
    SVC(),
    LinearSVC(),
    NuSVC()
]
```

### Evaluation Techniques
- 🔄 Cross-validation for reliable performance estimation
- 📈 Precision, Recall, and F1 Score for comprehensive evaluation

---

## 🏆 Results

| Model | Accuracy |
|-------|----------|
| Naive Bayes (with POS) | 95% |
| LinearSVC | 96% |

---

## 🔍 Key Findings

- ✅ POS-tagged features consistently boosted accuracy across models
- 📈 Bigram features showed significant improvement over unigram approach
- 🥇 LinearSVC emerged as the top-performing model for this dataset

---

## 🔮 Future Work

1. **Explore Advanced NLP**:
   - Word embeddings (Word2Vec, GloVe)
   - Deep learning models (LSTM, Transformers)

2. **Ensemble Methods**:
   - Investigate voting classifiers
   - Explore stacking techniques

3. **Preprocessing Optimization**:
   - Analyze impact of various preprocessing steps
   - Fine-tune tokenization and feature extraction

---

