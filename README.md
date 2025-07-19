# Day 6: FAISS + RAG Pipeline

🎯 This is a simple Retrieval Augmented Generation (RAG) pipeline demonstration, part of my 45‑day Generative AI & NLP learning journey.

It uses:
- 🧠 **SentenceTransformers** to create semantic embeddings
- 🔍 **FAISS** (Facebook AI Similarity Search) as a vector database
- 📝 A query → top‑k document retrieval workflow

---

## 🧪 **What This Code Does**
✅ Defines a small knowledge base of text documents  
✅ Converts them into dense vector embeddings  
✅ Stores them in a FAISS index for similarity search  
✅ Accepts a query, embeds it, and retrieves top‑k most relevant documents

Sample output:
The Eiffel Tower is in Paris.
The capital of France is Paris.
