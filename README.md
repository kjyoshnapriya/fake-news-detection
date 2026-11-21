# 📰 Fake News Detection

A machine learning project that classifies news articles as **Real** or **Fake** using Natural Language Processing (NLP). Paste any news article, and the model tells you whether it looks genuine or fabricated.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)
![Model](https://img.shields.io/badge/Model-Logistic%20Regression-green)

## 📌 Overview

Fake news spreads quickly online and can mislead people. This project builds a simple, beginner-friendly classifier that learns patterns in the language of real and fake news and uses them to predict the label of a new article.

## 📂 Dataset

- **ISOT Fake News Dataset**
- Contains two sets of articles: real news (`True.csv`) and fake news (`Fake.csv`)
- Each article has a title, text, subject, and date

## ⚙️ How It Works

1. **Load data:** Read the real and fake news files and add a label to each (Real = 1, Fake = 0).
2. **Clean text:** Convert to lowercase and remove punctuation, links, and unnecessary characters.
3. **Feature extraction:** Convert text into numbers using **TF-IDF** (Term Frequency, Inverse Document Frequency).
4. **Train model:** Train a **Logistic Regression** classifier on the training data.
5. **Evaluate:** Test the model on unseen data and check accuracy, precision, recall, and F1-score.
6. **Predict:** Paste a news article and get the result: Real or Fake.

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Platform | Google Colab |
| Libraries | pandas, NumPy, scikit-learn |
| Model | TF-IDF + Logistic Regression |

## 🚀 How to Run

1. Open `Fake_News_Detection_Project.ipynb` in **Google Colab**.
2. Upload the dataset files (`True.csv` and `Fake.csv`) to the Colab session.
3. Run all the cells from top to bottom (**Runtime → Run all**).
4. In the last cell, paste a news article and run it to see the prediction.

## 💡 Example

```
Input:  "Breaking: Scientists confirm ..."
Output: Real News ✅
```

## 📊 Results

- Accuracy: **XX%** *(replace with your result from the notebook)*

## ⚠️ Limitations

- The model learns from the writing style of the ISOT dataset, so it may not work perfectly on news from other sources.
- It checks language patterns, not whether the facts are actually true.

## 🔮 Future Improvements

- Try other models such as Naive Bayes, SVM, or deep learning (LSTM, BERT)
- Test on more datasets
- Build a simple web app for easy use

## 👩‍💻 Author

**Your Name**
GitHub: [kjyoshnapriya](https://github.com/kjyoshnapriya)
