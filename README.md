# 📘 Word Frequency in Classic Novels – Moby Dick (NLP + EDA Project)

This project analyzes **Herman Melville's Moby Dick** using **web scraping, data cleaning, EDA (Exploratory Data Analysis), and NLP (Natural Language Processing)** techniques. We extract the text from Project Gutenberg, clean it, and perform various levels of linguistic analysis including word frequency, stopword filtering, sentiment analysis, and visualizations.

---

## 📌 Project Objectives

- 📚 Scrape Moby Dick from Project Gutenberg
- 🧹 Clean and preprocess the novel’s text
- 📊 Perform Exploratory Data Analysis (EDA) on the text
- 🧠 Apply NLP techniques like:
  - Word frequency analysis
  - Stopword removal
  - Bigram/trigram analysis
  - Sentiment analysis
  - Named Entity Recognition (NER)
- 📈 Visualize results with bar plots and word clouds

---

## 🛠️ Tech Stack & Tools

- **Language:** Python  
- **Libraries:**  
  - `requests`, `BeautifulSoup` – Web Scraping  
  - `nltk`, `spacy`, `textblob` – NLP  
  - `pandas`, `re` – Data Analysis  
  - `matplotlib`, `seaborn`, `wordcloud` – Visualization  

---

## 🧩 Features

| Feature | Description |
|--------|-------------|
| ✅ Web Scraping | Pulls full text of Moby Dick from Project Gutenberg |
| ✅ Data Cleaning | Removes headers, footers, punctuation, and converts to lowercase |
| ✅ EDA | Analyzes word counts, sentence counts, unique words |
| ✅ NLP | Tokenization, stopword removal, bigram/trigram frequency |
| ✅ Sentiment Analysis | Detects the overall tone of the text |
| ✅ Visualizations | Bar plots, word cloud of top frequent words |
| ✅ NER (Optional) | Named entity extraction using spaCy |
| ✅ Chapter Analysis (Optional) | Word count and sentiment per chapter |

---

## 📊 Example EDA Output

- **Total Words:** 263,000+  
- **Unique Words:** 19,000+  
- **Top Words (after stopword removal):**  
  `whale`, `ahab`, `sea`, `ship`, `man`, ...

---

## 🖼️ Sample Visualizations

- Bar chart of top 20 most frequent words  
- Word cloud of filtered words  
- Sentiment polarity of each chapter  
- Frequency of bigrams like "white whale", "old man"
