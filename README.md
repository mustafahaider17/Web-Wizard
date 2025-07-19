# 🧙‍♂️ Web Wizard – AI-Powered Article Question Answering App

**Web Wizard** is an intelligent NLP-based Streamlit app that lets you input article/blog/documentation URLs and ask questions based on their content. It uses Gemini AI to generate answers from article context using FastText embeddings and FAISS-based semantic search.

---

## 🚀 Features

- 🔗 Input up to 3 article/blog URLs  
- 📄 Automatically scrapes and extracts clean text from each URL  
- ✂️ Splits text into chunks using Langchain  
- 🧠 Generates embeddings using FastText (Gensim)  
- 🔍 Finds the most relevant chunks using FAISS similarity search  
- 🤖 Sends selected context + your question to Gemini for a smart answer  
- ✅ Shows clean, AI-generated answers on-screen

---

## 🧰 Tech Stack

| Tool              | Purpose                        |
|-------------------|--------------------------------|
| Streamlit         | Web UI                         |
| BeautifulSoup     | Web scraping                   |
| Langchain         | Text chunking                  |
| FastText (Gensim) | Word embeddings                |
| FAISS             | Semantic similarity search     |
| Gemini API        | AI-generated answers           |
| Python            | Core language                  |

---

## 🔐 Environment Setup (.env file)

To use the Gemini API, create a `.env` file in the root directory of the project and add your API key like this:
You can get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
# example.env
GEMINI_API_KEY=your_api_key_here
