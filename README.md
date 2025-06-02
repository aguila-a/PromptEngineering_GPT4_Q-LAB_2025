# PromptEngineering_GPT4_Q-LAB_2025

This repository gathers my work from the **Prompt Engineering with GPT-4** summer course at **Q-LAB 2025**.  
It includes two main assignments and a final project, all developed in Google Colab.

---

## 📌 Contents

### 1️⃣ **Assignment 1: Document Assistant & Chatbot**
[View Colab notebook](https://colab.research.google.com/drive/1OAazGtZJDzitIQriMX5V9dT9FFZo5t2b?usp=sharing)

Summary:
- Processed the academic paper *Attention Is All You Need* (Vaswani et al., 2017).
- Split text into ~512-token chunks using `tiktoken`.
- Generated embeddings with `text-embedding-3-small`.
- Stored and queried the data using **ChromaDB**.
- Implemented a `retrieve_documents(query)` function to fetch the most relevant chunks.
- Built an interactive chatbot using `gpt-4o-mini`, capable of:
  - Producing structured outputs (summary, topics, sentiment).
  - Maintaining conversation history.
  - Solving math problems using **Chain-of-Thought** reasoning.

---

### 2️⃣ **Assignment 2: Advanced RAG & Multi-Agent Systems**
[View Colab notebook](https://colab.research.google.com/drive/1D9Umm-geNGnJ4HI7IOezcF_FiMmFVrJu?usp=sharing))

Summary:
- Developed advanced RAG (retrieval-augmented generation) chatbots:
  - Applied techniques like query transformation, proposition chunking, or HyDe embedding.
  - Compared basic vs. advanced RAG performance.
  - Integrated **function calling** to determine when retrieval was needed.
- Built a multi-agent system with **CrewAI** for event planning:
  - Included agents for venue coordination, logistics, marketing, and overall management.
  - Used web scraping and search-based retrieval where necessary.
  - Produced a final consolidated report summarizing all planning efforts.

---

### 3️⃣ **Final Project: Vocational Chatbot**
[View Colab notebook](https://colab.research.google.com/drive/1pJtgzFnTDxL7xTLJJ-sikg1sWnkd5Gks?usp=sharing))

Summary:
- Created a vocational guidance chatbot.
- Combined multiple agents and real-time information retrieval.
- Provided personalized academic and career recommendations.

---

## 🚀 Technologies Used
- Python, Google Colab
- OpenAI API (`gpt-4o-mini`, embeddings)
- ChromaDB
- CrewAI
- PyPDF2, tiktoken

---


