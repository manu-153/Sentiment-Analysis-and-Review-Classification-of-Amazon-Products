# 📦 Sentiment Analysis and Review Classification of Amazon Product


## 📌 Overview

This project performs **sentiment analysis** on Amazon product reviews using **TextBlob** and **VADER** sentiment analysis tools. The aim is to classify reviews into **positive**, **neutral**, and **negative** categories, and analyze how sentiment correlates with the given product ratings.

---

## 🚀 Key Features

* 🔍 **Sentiment Classification**
  Classified over **100,000+ Amazon reviews** into three sentiment categories using polarity and compound scores.

* 🧹 **Data Cleaning & Preprocessing**
  Built preprocessing pipelines including:

  * Text normalization
  * Stopwords removal
  * Punctuation and noise filtering
  * Handling of imbalanced sentiment labels

* 📊 **Visualization & Insights**

  * Analyzed sentiment distribution
  * Explored the impact of review sentiment on product star ratings
  * Plotted histograms, bar charts, and word clouds

---

## 📈 Results Summary

* **Average Ratings by Sentiment:**

  * ⭐ **Positive:** 4.74
  * ⚪ **Neutral:** 4.69
  * ❌ **Negative:** 3.61

* Observed that **positive reviews are highly correlated with higher product ratings**, while **negative sentiments show significant dips** in average rating scores.

---

## 🗂️ Dataset

* Source: [Amazon Product Reviews Dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews)
* Size: \~100,000 reviews
* Format: CSV with columns like `ReviewText`, `Summary`, `Score`, `Helpfulness`, etc.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Sentiment Tools:** `TextBlob`, `VADER` from `NLTK`
* **Data Processing:** `Pandas`, `NumPy`, `re`
* **Visualization:** `Matplotlib`, `Seaborn`, `WordCloud`
* **Jupyter Notebook** for exploration and presentation

---

## 📦 Installation

```bash
# Clone this repository
git clone https://github.com/your-username/amazon-review-sentiment.git
cd amazon-review-sentiment

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## ▶️ Usage

1. **Preprocess Data:**

   * Run `data_preprocessing.py` to clean and prepare the dataset.

2. **Sentiment Analysis:**

   * Use `sentiment_analysis_textblob.py` or `sentiment_analysis_vader.py` to perform sentiment classification.

3. **Visualization:**

   * Execute `visualization.py` to generate charts and word clouds.

---

## 📁 Repository Structure

```bash
📦amazon-review-sentiment
 ┣ 📂data
 ┃ ┗ 📄amazon_reviews.csv
 ┣ 📂notebooks
 ┃ ┗ 📄exploratory_analysis.ipynb
 ┣ 📂src
 ┃ ┣ 📄data_preprocessing.py
 ┃ ┣ 📄sentiment_analysis_textblob.py
 ┃ ┣ 📄sentiment_analysis_vader.py
 ┃ ┗ 📄visualization.py
 ┣ 📄requirements.txt
 ┗ 📄README.md
```

---

## ✅ Future Work

* Integrate deep learning models (e.g., LSTM, BERT) for improved sentiment classification.
* Add support for aspect-based sentiment analysis.
* Build a front-end to interact with reviews and show sentiment in real-time.

---

## 🤝 Contributing

Contributions are welcome! If you find bugs or have suggestions for improvements, feel free to open an issue or pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

