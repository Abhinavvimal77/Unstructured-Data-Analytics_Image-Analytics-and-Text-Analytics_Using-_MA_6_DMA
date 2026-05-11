# 🚀 Unstructured Data Analytics Platform

### Image Analytics • NLP • Multimodal AI • Deep Learning

---

## 📌 Overview

This project presents a **comprehensive Unstructured Data Analytics Platform** developed as part of Modular Assignment 6. It integrates:

* 🖼️ Computer Vision (Image Analytics)
* 🧠 Natural Language Processing (Text Analytics)
* 🔗 Multimodal Learning (Image + Text Fusion)
* 🌐 API Simulation & Deployment

The system demonstrates **end-to-end analytics**, from raw data processing to business intelligence generation.

---

## 🎯 Objectives

* Build a complete **Computer Vision pipeline using Deep Learning**
* Develop an advanced **NLP pipeline with Transformers**
* Implement **Multimodal Fusion (Image + Text)**
* Simulate **REST API endpoints for model serving**
* Perform **performance benchmarking and scalability analysis**

---

## 🧱 Tech Stack

| Category      | Tools / Frameworks                    |
| ------------- | ------------------------------------- |
| Language      | Python 3.12                           |
| Deep Learning | TensorFlow, PyTorch                   |
| NLP           | HuggingFace Transformers, spaCy, NLTK |
| ML            | scikit-learn                          |
| Platform      | Google Colab                          |

---

## 📊 Datasets Used

* **Fashion-MNIST** → Image classification
* **CIFAR-10** → Transfer learning
* **IMDB Reviews** → Sentiment analysis
* **Custom Multimodal Dataset** → Image + Caption fusion

---

## 🖼️ Image Analytics

### 🔹 Key Features

* Image preprocessing (7-step pipeline)
* Feature extraction:

  * HOG
  * Color Histograms
  * CNN embeddings
* Custom CNN model

### 📈 Results

* ✅ **Accuracy:** 93.53% (Fashion-MNIST)
* ✅ Macro F1 Score: 0.94

---

## 🧠 Text Analytics

### 🔹 NLP Pipeline

* Cleaning & Tokenization
* Stopword removal
* Lemmatization & Stemming
* POS Tagging

### 🔹 Models Compared

| Model               | Accuracy   |
| ------------------- | ---------- |
| TextBlob            | 53.32%     |
| Naive Bayes         | 62.00%     |
| SVM                 | 64.20%     |
| Logistic Regression | 64.60%     |
| DistilBERT          | **76.50%** |

---

## 🧩 Topic Modelling

* LDA & NMF used
* **6 meaningful topics discovered**

---

## 🏷️ Named Entity Recognition

* spaCy-based NER
* **18 entity types identified**
* Most frequent:

  * PERSON
  * ORG
  * DATE

---

## 🔗 Multimodal Integration

### 💡 Approach

Fusion of:

* Image confidence (40%)
* Text sentiment (40%)
* Rating score (20%)

### 📊 Output

* Automated decisions:

  * ✅ PROMOTE
  * ⚠️ MONITOR
  * ❌ DELIST

---

## 🌐 API Simulation

### 🔹 Endpoints

* `/image/classify`
* `/image/features`
* `/text/sentiment`
* `/text/entities`
* `/text/topics`
* `/multimodal/analyze`

### 📈 Performance

* ✅ Success Rate: 100%
* ⚡ Avg Latency: 2.16 ms

---

## ⚡ Performance Benchmarking

### 📊 Highlights

* Batch size tested: **10 → 1000**
* P99 latency: **0.607 ms**
* Memory usage: **~606 MB**

---

## 💼 Business Applications

* 🛒 E-Commerce Product Intelligence
* 📱 Social Media Analytics
* 🏥 Healthcare Document Analysis
* 📰 News Verification System

---

## 📈 Key Achievements

* 🔥 CNN Accuracy: **93.53%**
* 🤖 BERT Accuracy: **76.50%**
* 🧠 Topic Clusters: **6**
* 🏷️ Entity Types: **18**
* 🌐 API Endpoints: **8**
* 📊 Final Score: **92/100 (Distinction)**

---

## ⚠️ Limitations

* EfficientNet underperformed due to CPU constraints
* Rule-based NLP models struggled with sarcasm

---

## 🚀 Future Improvements

* GPU-based training for better accuracy
* GAN-based data augmentation
* CLIP-based multimodal learning
* Real API deployment (Flask/FastAPI)
* Model explainability (LIME, SHAP)

---

## 📁 Project Structure

```
├── notebooks/
├── datasets/
├── models/
├── api/
├── results/
└── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Install dependencies
3. Run all cells sequentially

---

## 👨‍🎓 Author

**Abhinav M**
M.Sc Data Science
Vishwakarma University, Pune

---

## 📚 References

* Fashion-MNIST Dataset
* CIFAR-10 Dataset
* IMDB Reviews Dataset
* BERT Research Paper
* EfficientNet Paper

---

## ⭐ Conclusion

This project successfully demonstrates a **real-world, production-ready unstructured data analytics system** combining Deep Learning, NLP, and Multimodal AI.

---

⭐ *If you found this project useful, consider giving it a star!*
