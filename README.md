# 📰 Fake News Detection AI

This project aims to detect fake news using Natural Language Processing (NLP) and Machine Learning techniques. We use a Passive Aggressive Classifier trained on real and fake news articles, and TF-IDF for text vectorization.

---

## 🚀 Demo

> ✅ Give it a news article and it tells you if it's **Real** or **Fake** using trained AI.

---

## 🧠 Algorithms Used

- TF-IDF Vectorizer (Text Preprocessing)
- Passive Aggressive Classifier (Model)

---

## 📁 Dataset

- **Fake.csv** – Fake news articles  
- **True.csv** – Real news articles

Source: [Kaggle Fake News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- TF-IDF
- Passive Aggressive Classifier
- Pickle

---

## 📊 Results

- ✅ Accuracy: **~92–95%**
- 💡 Efficient for fast and large-scale news detection
- 🔎 Works well on both short and long news articles

---

## 🧪 Try It Yourself

## 🧑‍💻 Author

**Muhammad Rayan Shahid**  
Passionate AI & ML Developer | [LinkedIn](https://www.linkedin.com/in/muhammadrayanshahid/) | [GitHub](https://github.com/RayanAIX)

---

⭐ If you found this project helpful, consider starring the repo!


```python
from fake_news_model import predict_news

predict_news("The government just passed a new law to support startups.")
# Output: Real or Fake
