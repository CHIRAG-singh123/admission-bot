# 🎓 LJ University Admission ChatBot

> *Empowering students with instant, accurate, and culturally connected admission guidance!*

![GitHub repo size](https://img.shields.io/github/repo-size/CHIRAG-singh123/lj-university-chatbot)
![GitHub last commit](https://img.shields.io/github/last-commit/CHIRAG-singh123/lj-university-chatbot)
![MIT License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/Made%20with-Python-blue)

---

## 🌟 Project Overview

**LJ University Admission ChatBot** is a feature-rich, AI-powered assistant designed to provide seamless support for student admission queries. Built with a sleek **Tkinter GUI** and advanced **NLP capabilities**, it offers fast, context-aware responses about:

🎓 Eligibility • 🎁 Scholarships • 🕒 Deadlines • 📋 Admission Process

---

## ✨ Key Features

- 🤖 **Natural Language Processing**: Tokenization, Lemmatization, TF-IDF via **NLTK**.
- 🧠 **Fuzzy FAQ Matching**: Smart matching using **FuzzyWuzzy** for user-friendly query handling.
- 🌐 **Multilingual Support**: Real-time translations with **Googletrans**.
- ✂️ **Text Summarization**: Summarize lengthy responses using **TextBlob**.
- 🎙️ **Speech Recognition (Optional)**: Voice input through **SpeechRecognition**.
- 💻 **Modern GUI**: Dark-themed, scrollable **Tkinter interface** with emoji and smooth UX.
- ❓ **Predefined FAQs**: Instant answers to common university-related queries.
- 🙏 **Cultural Greetings**: Replies with localized greetings like *Jay Shree Krishna* and *Namaste*.

---

## 🧠 How It Works

### 🛠 Input Processing
1. Translate input to English (`googletrans`)
2. Preprocess text: lowercase, remove punctuation, lemmatize (`nltk`)

### 🔁 Response Generation
- Detect greetings for cultural replies.
- Match FAQs via FuzzyWuzzy (≥75% similarity).
- Use TF-IDF + Cosine Similarity for corpus matching.
- Summarize lengthy responses using TextBlob.

### 🖥 GUI Interface
- Scrollable chat window with speaker labels (👤 You / 🤖 Bot)
- Supports `/bye` to exit and `/thanks` to acknowledge
- Voice input support (optional)

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/lj-university-chatbot.git
cd lj-university-chatbot
```

> Or navigate to your BOTS folder with `admission_bot_large.txt` and `chatbot_working.ipynb`.

### 2. Install Dependencies
```bash
pip install numpy pandas scikit-learn nltk textblob fuzzywuzzy googletrans==3.1.0a0 SpeechRecognition
pip install --upgrade pip  # If needed
```

### 3. Download NLTK Data
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

> Save above as `setup_nltk.py` and run with `python setup_nltk.py`.

### 4. Verify Corpus File
Ensure `admission_bot_large.txt` is located in your BOTS folder. Update file path in the notebook if needed.

### 5. Launch Jupyter Notebook
```bash
jupyter notebook
```

Navigate to `chatbot_working.ipynb` and run all cells.
For jupyter note book you can take help of this [video](https://youtu.be/8YGPfGDYAgI?si=UZFb_4p26i5hIo4R)

---

## 🚀 Usage Guide

1. Launch the notebook and Tkinter GUI will open.
2. Type your query in the input box or click **Send**.
3. For voice input (optional), configure microphone access.
4. Ask about admissions, deadlines, etc.
5. Exit with `bye`, thank with `thanks`.

### ✅ Example Queries
- “What are the eligibility criteria?”
- “Tell me about scholarships.”
- “Namaste, how do I apply?”
- “When is the application deadline?”

---

## 📊 Technologies Used

| Library           | Purpose                                               |
|------------------|-------------------------------------------------------|
| `Tkinter`        | GUI development (dark theme, scrollable chat)         |
| `NLTK`           | Text preprocessing: tokenization, lemmatization       |
| `Scikit-learn`   | TF-IDF + Cosine Similarity                            |
| `TextBlob`       | Summarization, sentiment (optional)                   |
| `FuzzyWuzzy`     | FAQ matching with similarity scoring                  |
| `Googletrans`    | Multilingual input translation                        |
| `SpeechRecognition` | Voice-to-text (optional)                           |
| `NumPy`          | Backend array operations for similarity checks        |

---

## 🎯 Results

- 🔍 **Accuracy**: >75% FAQ match with relevant responses
- 💬 **User Experience**: Intuitive interface + culturally tuned replies
- 📈 **Scalability**: Modular code supports advanced upgrades
- 🌎 **Multilingual**: Real-time translation for diverse users

---

## 🔮 Future Enhancements

- 🧠 **Sentiment Analysis**: Dynamic response tuning with VADER/TextBlob
- 💾 **Database Integration**: Replace static corpus with real-time DB
- 🔊 **Voice Output**: Enable text-to-speech for spoken replies
- 🌐 **Web Version**: Flask/Django deployment for cross-platform use
- 🤖 **Advanced NLP**: Integrate BERT or similar transformer models

---

## 🤝 Contributing

We ❤️ contributions!

```bash
# Steps to contribute
1. Fork the repo
2. Create a feature branch: git checkout -b feature/YourFeature
3. Commit your changes: git commit -m "Add YourFeature"
4. Push to GitHub: git push origin feature/YourFeature
5. Open a Pull Request 🚀
```

> For major changes, kindly open an issue first.

---

## 📜 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 👨‍💻 Author

**Chirag Singh**

- 🔗 [LinkedIn](https://www.linkedin.com/in/thechiragsingh/)
- 💻 [GitHub](https://github.com/CHIRAG-singh123)

---

> *“Built to serve students with speed, clarity, and a cultural touch.”*
