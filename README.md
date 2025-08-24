# Google SEO Guidelines for LLMs

This repository contains the official **Google Search Quality Evaluator Guidelines** and the **Google SEO Starter Guide**, reformatted into clean Markdown.  
They are optimized for use with **LLMs**, **semantic search**, and **Context7 integration**.

---

## 📚 Table of Contents
- [SEO Starter Guide](./seo_starter.md)  
- [Quality Rater Guidelines – Overview](./google_quality_raters_guidelines_overview.md)  
- [Quality Rater Guidelines – Full](./google_quality_raters_guidelines_final.md)  

---

## 🎯 Purpose
These documents are often referenced in SEO research, audits, and training.  
Here they are provided in a format optimized for:

- **Embedding in vector databases** (pgvector, Supabase, Pinecone, etc.)  
- **Context7 integration** for grounding AI assistants  
- **Semantic search & Retrieval-Augmented Generation (RAG)** projects  

---

## 🚀 Usage

### Context7
Add this repo in Context7 as a library. Then, in your AI workspace:

# context7 use [google-seo-guidelines]


This restricts your LLM to answers grounded in Google’s SEO guidelines.

### Supabase / LangChain
You can load these Markdown files, split them into chunks, and embed them with OpenAI’s `text-embedding-3-small` or `text-embedding-3-large`.

---

## 📌 Version
Last updated: **January 2025**  
Source: [Google](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) + official Quality Rater Guidelines PDF.

---

## ⚖️ License
The documents are © Google.  
This repo only reformats them into Markdown for **research and educational purposes**.  
No modifications were made to the meaning or intent of the content.
