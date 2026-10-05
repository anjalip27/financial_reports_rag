# Financial Reports RAG

## Objective
Build an evidence-grounded question-answering system over public annual reports.
Measure how retrieval choices affect answer quality, source accuracy, and latency.

## Dataset
Six annual reports: Microsoft and Alphabet, covering fiscal years 2022–2024.

## Planned Architecture
Documents → Parsing and Metadata → Chunking → Embeddings → Qdrant
→ Dense and BM25 Retrieval → Hybrid Retrieval → Reranking
→ LLM Answers with Citations → Evaluation

Later stages will add a conditional LangGraph workflow, FastAPI,
Docker, AWS deployment, and monitoring.

