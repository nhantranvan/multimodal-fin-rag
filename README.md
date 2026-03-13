# Multimodal Financial RAG 📊🔍

An advanced Retrieval-Augmented Generation (RAG) system specifically designed for financial analysts. This system processes complex PDF reports by simultaneously analyzing text, complex tables, and graphical charts using Vision-Language Models (VLMs).

## 💡 Key Challenges Addressed
- **Chart Interpretation:** Extracts insights directly from line charts, bar graphs, and pie charts.
- **Complex Table Parsing:** High-fidelity table extraction that maintains hierarchical relationships.
- **Contextual Reasoning:** Correlates visual data (e.g., a declining trend in a chart) with textual explanations (e.g., "supply chain issues").

## 🛠️ Technology Stack
- **VLM:** GPT-4o / LLaVA-1.6 for multimodal reasoning.
- **Vector DB:** Qdrant / Pinecone for indexing textual and visual embeddings.
- **Document Processing:** Unstructured.io / PyMuPDF.

## 🚀 Usage
```bash
python pipeline.py --pdf financial_report.pdf --query "Analyze the revenue growth in Q3"
```