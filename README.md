# RiskParse AI

**AI-Powered Legal Clause Risk Analyzer & Entity Extractor**

An intelligent NLP system that analyzes legal clauses, classifies risk levels, extracts legal entities, and provides visual attention heatmaps — trained on real SEC legal contracts.

## Features
- **Risk Classification:** Classifies legal clauses as HIGH RISK or LOW RISK using an NLP pipeline.
- **Explainability:** True Scaled Dot-Product Self-Attention mechanism generating interactive heatmaps.
- **Entity Extraction:** Extracts 7 entity types (MONETARY, DATE, PARTY, JURISDICTION, etc.).
- **Smart Summarization:** Extractive summarization to quickly read long clauses.
- **Modern UI:** Premium dark glassmorphism dashboard built with Streamlit and Plotly.

## Installation

```bash
pip install -r requirements.txt
streamlit run app.py
```
