# 📰 Fake News Detector

A machine learning project that classifies real vs. fake news using Natural Language Processing (NLP) and a Random Forest classifier.

## 📁 Dataset

- [Fake and Real News Dataset - Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Contains two CSV files: `True.csv` and `Fake.csv`

## 🧠 Model

- **Text cleaning** with NLTK (lowercasing, punctuation removal, stopwords)
- **Vectorization** using TF-IDF (max 5000 features)
- **Classifier**: Random Forest
- Achieves >90% accuracy on test data

## 📦 Requirements

Install dependencies with:

pip install -r requirements.txt

🚀 Usage
Download the dataset and place True.csv and Fake.csv in the data/ folder.

Run the Jupyter Notebook inside the notebooks/ folder:

notebooks/fake_news_classifier.ipynb

📂 Project Structure

fake-news-detector/
├── data/
│   ├── True.csv
│   └── Fake.csv
├── notebooks/
│   └── fake_news_classifier.ipynb
├── requirements.txt
├── .gitignore
└── README.md
