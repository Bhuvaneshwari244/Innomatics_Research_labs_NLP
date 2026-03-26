# Innomatics_Research_labs_NLP

# 🧠 NLP Preprocessing Engine (Advanced)

**Internship:** Data Science Internship - February 2026
**Company:** Innomatics Research Labs / Technology Hub
**Task:** Task 1 - Build a Robust NLP Preprocessing Engine

## 📌 Project Overview
In real-world Natural Language Processing (NLP) systems, raw text data is often noisy, inconsistent, and unstructured. This project features a production-quality, modular NLP preprocessing pipeline built in Python to transform messy, real-world textual data into clean, structured, and meaningful tokens suitable for machine learning models.

## 🚀 Features & Implementation
This repository contains a Jupyter Notebook (`.ipynb`) that successfully implements the following requirements:

* **Conceptual Foundation (Task 1):** Detailed explanations of core NLP concepts including Stopwords, Stemming vs. Lemmatization, and token normalization.
* **Advanced Preprocessing Engine (Task 2):** A custom Python function that uses Regular Expressions (`re`) to:
    * Remove URLs and email-like patterns.
    * Strip out numbers and extra whitespaces.
    * Handle repeated characters (e.g., "soooo goooood!!!" → "so good").
    * Convert text to lowercase for uniformity.
    * Filter out very short tokens (length <= 2), while explicitly preserving critical context words like "no" and "not".
* **Stress Testing (Task 3):** Validated the engine against 10 diverse sentences containing emojis, slang, mixed cases, and extreme punctuation.
* **Token Analytics (Task 4):** Automated computation of total tokens, unique tokens, and average token length per sentence.
* **Frequency Analysis (Task 5):** Aggregated token analysis to identify the Top 10 most frequent and Top 5 least frequent words using `collections.Counter`.
* **Full Pipeline Architecture (Task 6):** A wrapper function capable of processing lists of text into separated tokens and clean sentences.
* **Robust Error Handling (Task 7):** Graceful handling of edge cases such as empty strings, emoji-only inputs, and number-only strings to prevent pipeline crashes.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** `re` (Regular Expressions), `collections`
* **Environment:** Jupyter Notebook / Google Colab

## 💻 How to Run
1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed, or upload the file to Google Colab.
3. Open the `Task_1_NLP_Preprocessing.ipynb` file.
4. Run the cells sequentially to observe the pipeline cleaning the text and generating the analytics.

---
*Developed as part of the Logic Building & Data Science Assessment for the Feb 2026 Cohort.*
