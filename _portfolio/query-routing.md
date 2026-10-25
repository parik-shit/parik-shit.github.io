---
title: "Embedding-Based Query Routing over a Local Document Corpus"
excerpt: "Routes a natural-language query to the correct source document using locally hosted embeddings, so document contents and queries never leave the machine."
collection: portfolio
---

**Stack:** Python, LangChain, Ollama, scikit-learn, PyPDF2

**Links:** [GitHub](https://github.com/parik-shit/query-routing-RAG)

* Routes a natural-language query to the correct source document by chunking each corpus, embedding the chunks, and picking the corpus with the highest cosine similarity to the query.
* Runs embedding inference locally through a self-hosted model rather than a hosted API, so document contents and queries never leave the machine.
