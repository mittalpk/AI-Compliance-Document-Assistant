# AI Compliance Document Assistant

An end-to-end, Free Edition–compatible solution for extracting, indexing, and querying German regulatory PDFs  
(GwG, MaRisk, ESG/EBA Guidelines) using Retrieval-Augmented Generation (RAG).

### What It Does
- Extracts text from PDFs stored in Unity Catalog Volumes  
- Splits documents into safe, token-controlled chunks  
- Generates embeddings using OpenAI  
- Builds an in-memory FAISS vector index  
- Answers compliance questions with GPT-4o-mini  
- Returns source snippets for full explainability  

### Why Free Edition?
Databricks Free Edition does not support:
- `ai_parse_document`
- Vector Search  
- Model Serving  
- DBFS  

This assistant recreates the complete workflow **without any premium features**,  
while remaining fully upgradeable to Databricks Document Intelligence.

### Notebook
- `AI-Compliance-Document-Assistant.ipynb` (located in the root directory)

### Documentation
See `architecture.md` for pipeline architecture  

---
