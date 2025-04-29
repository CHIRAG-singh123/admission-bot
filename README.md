🎓 LJ University Admission ChatBot
A Feature-Rich, AI-Powered ChatBot for Seamless University Admission Queries

🌟 Project Overview
Welcome to the LJ University Admission ChatBot, an advanced, user-friendly conversational AI designed to assist prospective students with university admission queries. Built with a modern Tkinter GUI and powered by cutting-edge NLP techniques, this chatbot provides accurate, context-aware responses to questions about eligibility, scholarships, deadlines, and more.
✨ Key Features

Natural Language Processing: Utilizes NLTK for tokenization, lemmatization, and TF-IDF for intelligent response matching.
Fuzzy FAQ Matching: Leverages FuzzyWuzzy for robust FAQ handling, ensuring accurate answers even for imprecise queries.
Multilingual Support: Integrates Googletrans for real-time translation of user inputs into English.
Text Summarization: Employs TextBlob to deliver concise, meaningful responses.
Speech Recognition (Optional): Supports speech-to-text input using SpeechRecognition for accessibility.
Modern GUI: A sleek, responsive Tkinter interface with a dark theme, emoji support, and smooth user experience.
Predefined FAQs: Instant answers to common queries like eligibility, admission process, and contact information.
Cultural Greetings: Personalized responses with culturally relevant greetings like "Jay Shree Krishna" and "Namaste."


📚 How It Works

Input Processing:

User inputs (text or speech) are translated to English using Googletrans.
Text is preprocessed (lowercased, punctuation removed, lemmatized) using NLTK.


Response Generation:

Checks for greetings and responds with culturally relevant replies.
Matches queries against predefined FAQs using FuzzyWuzzy (75%+ similarity).
Uses TF-IDF and cosine similarity to find relevant responses from a corpus.
Summarizes long responses with TextBlob for clarity.


User Interface:

Displays conversations in a scrollable chat area with sender labels (e.g., "👤 You", "🤖 Bot").
Supports commands like "bye" to exit and "thanks" for polite acknowledgments.


Extensibility:

Modular design allows easy integration of new features like sentiment analysis or advanced ML models.




🛠️ Installation
Get started with the LJ University Admission ChatBot in just a few steps!
Prerequisites

Python 3.8+
A corpus file (admission_bot_large.txt) with admission-related data.

Setup Instructions

Clone the Repository:
git clone https://github.com/your-username/lj-university-chatbot.git
cd lj-university-chatbot


Install Dependencies:
pip install numpy pandas scikit-learn nltk textblob fuzzywuzzy googletrans==3.1.0a0 SpeechRecognition


Download NLTK Data:
import nltk
nltk.download('punkt')
nltk.download('wordnet')


Prepare Corpus:

Place your admission_bot_large.txt file in the project directory or update the file path in the code.


Run the ChatBot:
python chatbot.py

### Run codes in jupyter nootbook.
Take help from youtube video.
[Youtube](https://youtu.be/8YGPfGDYAgI?si=UZFb_4p26i5hIo4R)



🚀 Usage

Launch the application to see the Tkinter GUI with a welcome message.
Type your query in the input field or press "Send" (or hit Enter).
For speech input (if enabled), use the microphone option (requires SpeechRecognition setup).
Ask about admissions, scholarships, deadlines, or greet the bot with "Hi" or "Hello."
Type "bye" to exit or "thanks" for a polite response.

Example Queries

"What are the eligibility criteria?"
"Tell me about scholarships."
"When is the application deadline?"
"Namaste, how do I apply?"


📊 Technologies Used



Library
Purpose



Tkinter
Modern GUI with scrollable chat and interactive buttons


NLTK
Text tokenization, lemmatization, and preprocessing


Scikit-learn
TF-IDF vectorization and cosine similarity for response matching


TextBlob
Text summarization and sentiment analysis (optional)


FuzzyWuzzy
Fuzzy matching for robust FAQ handling


Googletrans
Real-time translation for multilingual support


SpeechRecognition
Speech-to-text input (optional)


NumPy
Efficient array operations for similarity calculations



🎯 Results

Accuracy: Achieves high response relevance with TF-IDF and fuzzy matching (>75% FAQ match threshold).
User Experience: Smooth, intuitive GUI with culturally tailored responses.
Scalability: Easily extensible for additional features like sentiment analysis or database integration.
Multilingual: Handles queries in multiple languages via translation.


🔮 Future Enhancements

Sentiment Analysis: Integrate TextBlob or VADER for analyzing user sentiment and tailoring responses.
Database Integration: Replace corpus file with a database for dynamic updates.
Voice Output: Add text-to-speech for audio responses.
Web Deployment: Convert to a web app using Flask or Django for broader accessibility.
Advanced NLP: Incorporate transformers (e.g., BERT) for improved context understanding.


🤝 Contributing
We welcome contributions to make the LJ University Admission ChatBot even better! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/YourFeature).
Commit changes (git commit -m "Add YourFeature").
Push to the branch (git push origin feature/YourFeature).
Open a pull request.

Please open an issue first for major changes or new features.

📜 License
This project is licensed under the MIT License.

👨‍💻 Author

CHIRAG SINGH
- LinkedIn: [Linkedin](https://www.linkedin.com/in/thechiragsingh/)
- GitHub: [Github](https://github.com/CHIRAG-singh123)



"Empowering students with instant, accurate, and culturally connected admission guidance!"


