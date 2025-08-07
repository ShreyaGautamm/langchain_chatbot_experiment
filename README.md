# 🤖 LangChain Q&A Chatbot Experiments

This repo is part of my personal experimentation with **LangChain** — focused on building **question-answering chatbots** with **chat history**, **context awareness**, and **retrieval-augmented generation (RAG)**.

The goal: to explore how memory, prompt engineering, and external context can work together to create more natural and grounded conversations with LLMs.

---

## 🧪 What I Explored

- 🧠 **Chat Memory** using `RunnableWithMessageHistory`  
  Handle multiple conversations with session-based memory.

- 🔍 **RAG (Retrieval-Augmented Generation)**  
  Pull answers from external web sources using `WebBaseLoader` and `HuggingFace` embeddings into `Chroma`.

- 💬 **Prompt Templates & System Messages**  
  Design flexible, modular prompts to guide LLM behavior effectively.

- ⚡ **Fast Inference with Groq**  
  Use Groq-hosted models like LLaMA 3 and Gemma for quick and cost-effective inference.

---

## 🛠️ Tools & Libraries

<p align="left">
  <a href="https://www.langchain.com/" target="_blank"><img src="https://img.shields.io/badge/LangChain-%230073e6?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjZmZmIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGQ9Ik0xMCAwQzQuNDggMCAwIDQuNDggMCAxMHM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTUuNTIgMCAxMCAweiIvPjwvc3ZnPg==" alt="LangChain"></a>
  <a href="https://groq.com/" target="_blank"><img src="https://img.shields.io/badge/Groq_LLMs-%23ff6f00?style=for-the-badge" alt="Groq"></a>
  <a href="https://www.chroma.dev/" target="_blank"><img src="https://img.shields.io/badge/Chroma_DB-%234197f1?style=for-the-badge" alt="ChromaDB"></a>
  <a href="https://huggingface.co/" target="_blank"><img src="https://img.shields.io/badge/HuggingFace_Embeddings-%23ffcd00?style=for-the-badge&logo=huggingface" alt="HuggingFace"></a>
  <a href="https://www.crummy.com/software/BeautifulSoup/" target="_blank"><img src="https://img.shields.io/badge/BeautifulSoup-%23006400?style=for-the-badge" alt="BeautifulSoup"></a>
</p>

---

## 🔐 API Keys Required

- [Groq API Key](https://console.groq.com/)
- [Hugging Face Hub Token](https://huggingface.co/settings/tokens)
- [LangChain API Key](https://www.langchain.com/)

Set them in your `.env` file like so:
```env
LANGCHAIN_API_KEY=your-langchain-api-key
GROQ_API_KEY=your-groq-api-key
HF_TOKEN=your-huggingface-token
