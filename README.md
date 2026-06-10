# HealthScribe-AI 🩺

AI-powered medical report simplification system built using Generative AI, RAG, and NLP techniques to convert complex clinical reports into patient-friendly explanations.

## Overview

HealthScribe-AI bridges the communication gap between healthcare professionals and patients by transforming technical medical reports into easy-to-understand explanations.

The system combines:

* Fine-tuned Google Gemma-2B-IT using QLoRA
* Retrieval-Augmented Generation (RAG)
* FAISS Vector Search
* Medical Entity Extraction
* Abnormal Value Detection
* Streamlit Web Interface

Users can upload or paste medical laboratory reports and receive clear explanations, abnormal value alerts, and similar historical case references.

## Features

✅ Medical report simplification using LLMs

✅ Fine-tuned Gemma-2B-IT with LoRA

✅ Retrieval-Augmented Generation (RAG)

✅ Medical entity extraction using spaCy

✅ Rule-based abnormal value detection

✅ Similar case retrieval with FAISS

✅ SQLite history storage

✅ Streamlit web application

✅ Google Drive persistence for model recovery

---

## Architecture

Medical Report
↓
Preprocessing
↓
Entity Extraction + Abnormal Value Detection
↓
FAISS Similarity Search
↓
Gemma-2B-IT + QLoRA
↓
Patient-Friendly Explanation
↓
Streamlit Dashboard

---

## Tech Stack

| Category        | Technology            |
| --------------- | --------------------- |
| Language        | Python                |
| LLM             | Gemma-2B-IT           |
| Fine-Tuning     | QLoRA, PEFT           |
| NLP             | spaCy                 |
| Embeddings      | Sentence Transformers |
| Vector Database | FAISS                 |
| Frontend        | Streamlit             |
| Database        | SQLite                |
| Evaluation      | ROUGE, BLEU           |
| Platform        | Google Colab          |

---

## Results

| Metric  | Baseline | Fine-Tuned |
| ------- | -------- | ---------- |
| ROUGE-1 | 0.0468   | 0.9257     |
| ROUGE-2 | 0.0010   | 0.8771     |
| ROUGE-L | 0.0343   | 0.9201     |
| BLEU    | 0.0040   | 0.8462     |

### Key Achievements

* 87%+ improvement in ROUGE scores
* 84% improvement in BLEU score
* Retrieval latency under 5ms using FAISS
* Complete end-to-end deployment with Streamlit

---

## Project Structure

```text
HealthScribe-AI/
│
├── data/
├── models/
├── notebooks/
├── faiss_index/
├── streamlit_app/
├── evaluation/
├── utils/
├── requirements.txt
├── README.md
└── app.py
```

## Future Enhancements

* Support for radiology reports
* Multilingual explanations
* Advanced RAG pipelines
* FastAPI deployment
* Personalized explanations using patient history
* Larger clinical datasets

## Disclaimer

This project is intended for educational and research purposes only. It does not provide medical diagnoses and should not replace professional medical advice.

## Author

**Sarvesh Solanki**
B.Tech CSE, BML Munjal University

