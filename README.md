# Spelling Correction Using Jaccard Similarity

## 📖 Project Overview
This project implements a spelling correction system using the **Jaccard Similarity** algorithm. It compares misspelled words with a dictionary of valid words by calculating the similarity between character sets or n-grams. The system suggests the most similar correct word, demonstrating the application of set-based similarity measures in Natural Language Processing (NLP).

---

## 🎯 Objectives
- Detect misspelled words.
- Calculate Jaccard similarity between words.
- Suggest the most similar correct spelling.
- Demonstrate the use of NLP techniques for text correction.

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK (if used)
- Regular Expressions (Regex)

---

## ⚙️ How It Works
1. Load a dictionary of valid words.
2. Convert words into character sets or n-grams.
3. Compute the Jaccard Similarity score between the input word and dictionary words.
4. Return the word with the highest similarity score as the correction.

---

## 📂 Project Structure

```
Spelling-Correction-Using-Jaccard-Similarity/
│
├── Spelling Correction Using Jaccard Similarity.ipynb
├── README.md
└── dataset/ (if applicable)
```

---

## 📊 Features
- Text preprocessing
- Jaccard Similarity computation
- Misspelled word detection
- Best-match word suggestion
- Easy-to-understand implementation

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spelling-correction-jaccard.git
   ```

2. Install the required libraries:
   ```bash
   pip install pandas numpy nltk
   ```

3. Open the notebook:
   ```bash
   jupyter notebook
   ```

4. Run **Spelling Correction Using Jaccard Similarity.ipynb**.

---

## 📈 Results
The project successfully identifies the closest matching word for misspelled inputs using the Jaccard Similarity metric, demonstrating an effective and simple approach to spelling correction.

---

## 🔮 Future Improvements
- Add support for large dictionaries.
- Compare Jaccard Similarity with Levenshtein Distance and Cosine Similarity.
- Build a web application using Flask or Streamlit.
- Improve accuracy using word frequency and language models.

---

## 👨‍💻 Author
**Akshara Pandey**

If you found this project helpful, consider giving it a ⭐ on GitHub!
