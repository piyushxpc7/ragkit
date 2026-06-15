# ragkit

**A toolkit of RAG patterns in Python.** A working collection of retrieval-augmented-generation building blocks and reference implementations — the patterns you actually reach for, in one place.

## Inside
| File | Pattern |
|---|---|
| `basic_hedgefund_query_rag.py` | End-to-end RAG query engine over hedge-fund data |
| `pe_rag.py` | Private-equity document RAG |
| `chunking_strategy.py` | Comparison of chunking strategies |
| `file_type_extraction_rag.py` | Multi-format ingestion (PDF, docs, …) |
| `rag-chroma-faiss.py` | Chroma vs FAISS multi-store retrieval |
| `rageval.py` | Evaluation harness for RAG quality |

## Quick start
```bash
pip install -r requirements.txt   # or install per-script deps
export OPENAI_API_KEY=...
python basic_hedgefund_query_rag.py
```
