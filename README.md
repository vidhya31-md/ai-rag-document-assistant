# Enterprise RAG Document Assistant 🚀

An end-to-end Retrieval-Augmented Generation (RAG) backend pipeline built with **Python**, **FastAPI**, **LangChain concepts**, and structured LLM evaluation metrics. Designed for scalable enterprise document querying and context-aware information retrieval.

## 🛠 Tech Stack & Frameworks
- **Language:** Python 3.10+
- **API Framework:** FastAPI
- **LLM Orchestration:** LangChain / Vector Embeddings simulation
- **Evaluation:** Ragas & DeepEval metrics alignment (Precision, Recall, F1)

## 📌 Features
1. **Document Ingestion & Vector Storage:** Endpoint to process, chunk, and store text vector embeddings.
2. **Context-Aware RAG Retrieval:** Dynamically fetches top-k relevant context chunks based on semantic similarity.
3. **Structured Prompting:** Formats retrieved information into clean prompt schemas for reliable model outputs.
4. **LLM Evaluation Logging:** Integrates baseline precision and recall metrics to track response accuracy.

## ⚙️ How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/vidhya31-md/ai-rag-document-assistant.git](https://github.com/vidhya31-md/ai-rag-document-assistant.git)
   cd ai-rag-document-assistant
