# 🕸️ Website Scraper + RAG Agent

This project combines automated web data collection with a Retrieval-Augmented Generation (RAG) agent to deliver intelligent, context-aware responses from a custom knowledge base.

---

## 📖 Overview

The system automatically **scrapes a target website**, structures the extracted information, and builds a **knowledge base** that can be queried through an AI-powered agent.  
Using RAG, the agent retrieves the most relevant information and generates natural, human-like answers for visitors.

This ensures responses are both:
- ✅ **Accurate** (grounded in real scraped data)  
- 🤖 **Intelligent** (enhanced with generative AI reasoning)  

---

## ⚙️ Tech Stack

- **[Supabase](https://supabase.com/)** – Vector database for embeddings & semantic search.  
- **[Streamlit](https://streamlit.io/)** – Interactive web app for the RAG agent interface.  
- **[Pydantic AI](https://github.com/pydantic/pydantic-ai)** – Data validation and schema management.  
- **[Crawl4AI](https://github.com/Owner/crawl4ai)** – Automated website scraping engine.  

---

## 🚀 Features

- 🌐 Automated **website crawling** to build/update the knowledge base.  
- 🔎 **Semantic search** over scraped content via embeddings.  
- 🧠 **Retrieval-Augmented Generation (RAG)** for context-aware answers.  
- 💬 Simple & user-friendly **Streamlit chat interface**.  
- 📦 Scalable backend using **Supabase** for storage & retrieval.  

---

## 🔍 Use Cases

- Customer support automation.  
- Domain-specific Q&A assistants.  
- Knowledge discovery from frequently updated websites.  
- AI-powered documentation helpers.  


    B --> C[Vector Embeddings + Semantic Search]
    C --> D[RAG Agent (Pydantic AI)]
    D --> E[Streamlit Chat Interface]
    E --> F[User Queries & Responses]
