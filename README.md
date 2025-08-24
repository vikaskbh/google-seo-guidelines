# Google SEO Guidelines for LLMs

This repository contains the official **Google Search Quality Evaluator Guidelines** and **SEO Starter Guide**, reformatted into clean Markdown for use with **LLMs and semantic search**.

## Contents
- `google_quality_raters_guidelines.md` – Full rater guidelines  
- `google_quality_raters_guidelines_overview.md` – Condensed overview  
- `seo_starter.md` – Google SEO Starter Guide  

## Purpose
These documents are often referenced in SEO research, audits, and training.  
Here they are provided in a format optimized for:
- **Embedding in vector databases (pgvector, Supabase, etc.)**
- **Context7 integration** (so you can ground LLMs with the latest guidelines)
- **Semantic search** and retrieval-augmented generation (RAG) projects

## Usage
If you’re using **Context7**, you can add this repo as a library and then call:

```context7 use [google-seo-guidelines]```


to restrict your AI assistant to answers grounded only in Google’s SEO guidelines.

For Supabase or LangChain, you can load these Markdown files, split them into chunks, and embed them using OpenAI’s `text-embedding-3-small` or `text-embedding-3-large`.

## License
These documents are © Google. Reformatted here for research and educational purposes.  
No modifications were made to the meaning or intent of the content.
