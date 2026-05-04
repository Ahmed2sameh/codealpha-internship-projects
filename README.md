# CodeAlpha Internship Projects

> NLP projects completed as part of the CodeAlpha internship program.

## 📁 Projects

### 1. 🤖 FAQ Chatbot (`chatbot_for_faqs.ipynb`)
A rule-based chatbot that answers questions about AI and machine learning concepts using **TF-IDF vectorization** and **cosine similarity** for intent matching.

**How it works:**
- FAQ knowledge base defined as key-value pairs
- User query is vectorized with TF-IDF
- Cosine similarity finds the best matching question
- Returns the corresponding answer (or fallback if confidence < 0.3)

**Stack:** Python, scikit-learn, NLTK

---

### 2. 🌐 Language Translation Tool (`language_translation_tool.ipynb`)
An interactive translation tool supporting multiple languages using the **deep-translator** library (Google Translate API wrapper).

**How it works:**
- User inputs source language, target language, and text
- `GoogleTranslator` handles the translation
- Clean CLI interface with error handling

**Stack:** Python, deep-translator

---

## 🧰 Technologies Used
- **Python 3**
- **scikit-learn** — TF-IDF, cosine similarity
- **NLTK** — Natural language toolkit
- **deep-translator** — Google Translate wrapper

## 🚀 How to Run
1. Open either notebook in Google Colab
2. Run all cells — dependencies install automatically
3. Interact via the input prompts

## 📂 Project Structure
```
├── chatbot_for_faqs.ipynb          # TF-IDF FAQ chatbot
├── language_translation_tool.ipynb # Multi-language translation tool
└── README.md
```

## 👤 Author
Ahmed Sameh — [GitHub](https://github.com/Ahmed2sameh)
