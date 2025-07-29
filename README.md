# 620-mod6-web-scraping

See [BeautifulSoup Quickstart Guide](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start)

Choose a BeautifulSoup parser:

- 'html.parser' (default, you get this with BeautifulSoup)
- 'html5lib' (install separately if desired)

## Getting Started

Fork (copy into your GitHub account) and clone down (to your machine) this repo to get started with web scraping.

# 🧠 D6: Web Scraping and NLP — MS Data Analytics

**Author:** Huzaifa Nadeem  
**Course:** Data Analytics | Northwest Missouri State University  
**Module:** 6 — Web Scraping & Natural Language Processing (NLP)  
**Date:** July 2025

---

## 📌 Project Summary

This assignment demonstrates web scraping and sentiment analysis using Python. The main goal is to extract article content from the web, clean and analyze the text using spaCy and the spaCyTextBlob extension, and explore linguistic insights such as:

- Article polarity (positive/negative tone)
- Most frequent meaningful terms
- Lemmatization and token filtering
- "Cool word" scoring per sentence

---

## 🛠 Tools & Libraries Used

- `requests` — for downloading HTML pages
- `beautifulsoup4` — for parsing HTML
- `pickle` — for saving the HTML content locally
- `spacy` — for NLP tokenization and analysis
- `spacytextblob` — for sentiment scoring
- `Counter` — for word frequency analysis
- `matplotlib` — (installed, though not used)

---

## ⚙️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/HuzaifaUCMO/620-mod6-web-scraping
   cd YOUR-REPO

