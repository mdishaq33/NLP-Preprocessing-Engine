# NLP Preprocessing Engine

## 📌 Project Overview

This project is part of my Data Science Internship (February 2026).
The goal was to build a robust NLP preprocessing system that can clean and transform messy real-world text into structured data.

---

## 🚀 What I Built

I developed a preprocessing pipeline that:

* Cleans raw text data
* Removes noise like numbers, URLs, and special characters
* Handles repeated characters (e.g., "soooo" → "so")
* Converts text to lowercase
* Removes unnecessary short words (while keeping meaningful words like "no" and "not")
* Generates clean tokens and sentences

---

## 🛠️ Technologies Used

* Python
* Regular Expressions (re)
* Collections (Counter)
* Jupyter Notebook / Google Colab

---

## ⚙️ Features

* Text normalization (lowercase, clean formatting)
* Noise removal (numbers, emojis, URLs)
* Tokenization
* Token-level analytics (count, unique words, average length)
* Frequency analysis (most and least common words)
* Full NLP pipeline for batch processing
* Error handling for edge cases (empty text, only numbers, emojis)

---

## 📊 Example Output

Input:
"I absolutely looooved this product 😍😍"

Output:

* Tokens: ['absolutely', 'loved', 'this', 'product']
* Clean Sentence: "absolutely loved this product"

---

## 💡 What I Learned

* How real-world text data is noisy and needs preprocessing
* How to build a step-by-step NLP pipeline
* Basics of text cleaning using regular expressions
* Importance of handling edge cases in real data
* Writing clean and modular Python code

---

## ⚠️ Challenges Faced

* Handling repeated characters without breaking correct words
* Writing correct regex patterns
* Understanding tokenization and filtering logic

---

## ✅ How I Solved Them

* Improved regex logic to handle only excessive repetitions
* Tested the function on multiple real-world examples
* Debugged step-by-step to fix errors and improve accuracy

---

## 📌 Conclusion

This project helped me understand the importance of preprocessing in NLP and how clean data improves model performance. It gave me hands-on experience in building a real-world data cleaning pipeline.

---

## 👨‍💻 Author

Mohd Ishaq 
