flowchart LR

    A1[PDFs in UC Volume<br>(GwG, MaRisk, ESG)] --> B1[Consolidated Notebook:<br>AI-Compliance-Document-Assistant.ipynb]
    B1 --> C1[Delta Table:<br>extracted_text]
    C1 --> D1[Token-Based Chunking]
    D1 --> E1[Chunked Text DF]
    E1 --> F1[OpenAI Embeddings]
    F1 --> G1[FAISS Index]
    G1 --> H1[RAG Engine]
    H1 --> I1[Answer + Source Chunks]

    subgraph Databricks Free Edition
      B1
      C1
      D1
      E1
      F1
      G1
      H1
      I1
    end
