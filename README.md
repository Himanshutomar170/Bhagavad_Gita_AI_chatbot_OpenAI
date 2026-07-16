# Bhagavad_Gita_AI_chatbot_OpenAI
# 🕉️ AI-Powered Bhagavad Gita Chatbot (RAG)

An AI-powered chatbot that answers life-related questions using the teachings of the Bhagavad Gita. The application uses Retrieval-Augmented Generation (RAG) to retrieve relevant verses from the Bhagavad Gita and generate meaningful responses with the help of OpenAI GPT.

---

## 📌 Features

- 📄 Extracts text from the Bhagavad Gita PDF
- ✂️ Splits text into searchable verses
- 🔍 Semantic search using FAISS
- 🧠 Sentence Transformer embeddings
- 🤖 GPT-powered answer generation
- 🎲 Random Bhagavad Gita verse explanation
- 💬 Interactive Gradio web interface

---

## 🛠️ Tech Stack

- Python
- OpenAI GPT
- LangChain
- FAISS
- Sentence Transformers
- PyMuPDF
- Gradio


---

## 🚀 How It Works

1. Load the Bhagavad Gita PDF.
2. Extract all text from the document.
3. Split the text into individual verses.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector database.
6. Convert the user's question into an embedding.
7. Retrieve the most relevant verses.
8. Send the retrieved verses along with the user's question to GPT.
9. Display a meaningful answer based on the Bhagavad Gita.

---

## 📂 Project Structure

```
Bhagavad-Gita-RAG/
│
├── bhagavad_gita.pdf
├── requirements.txt
└── README.md
```

---

## 💡 Example Questions

- How can I overcome fear?
- How should I handle failure?
- What does the Bhagavad Gita say about anger?
- How can I stay calm during difficult times?
- How should I perform my duties?

---

## 📷 Output

The chatbot retrieves the most relevant Bhagavad Gita verses and generates an easy-to-understand explanation using GPT.

---

## 🔮 Future Improvements

- Support multiple spiritual books
- Voice-based interaction
- Multi-language support
- Verse citation with chapter and verse number
- Conversation history
- Improved retrieval using advanced RAG techniques

---

## 📚 Learning Outcomes

This project helped me understand:

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases (FAISS)
- Sentence Embeddings
- Prompt Engineering
- OpenAI API Integration
- Building AI applications with Python

---

## ⚠️ Note

To run this project, add your own OpenAI API key before execution.

```


