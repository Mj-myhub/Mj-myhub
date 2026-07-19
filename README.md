# Hi, I'm Majid Jafari

**NLP Researcher | LLMs, RAG & Agentic Systems | Computational Linguistics**

I'm a computational linguist based in Rome, working at the intersection of large language models, transformer architectures, and the connection between language, cognition, and AI. Lately my focus has shifted toward building and rigorously evaluating LLM systems - retrieval-augmented generation, agentic pipelines, and multilingual evaluation harnesses - rather than just studying language models from a distance.

My master's thesis at the University of Siena explored how deep learning models can be used to study language development. I fine-tuned GPT-2 on child-directed speech from the CHILDES database and tested the models on wh-questions, Berko's wug test, aux-less questions, and other psycholinguistically motivated tasks, focusing on how transformer-based models handle linguistic structure and generalisation.

Since then I've moved into applied NLP engineering: building systems that don't just work, but that know - and can prove - what they do and don't know. That theme runs through most of my recent projects: verified vs. unverified corrections, cited vs. abstained answers, and judges that are audited rather than trusted blindly.

## What I'm working on

- Agentic LLM systems (LangGraph) for real-world tasks like writing tutoring
- Retrieval-augmented generation - hybrid BM25 + dense retrieval, reranking, query expansion
- Evaluation-driven NLP: measuring precision/recall tradeoffs honestly instead of asserting quality
- Multilingual evaluation of hallucination/faithfulness judges (English, Italian, Persian)
- Deploying ML systems end-to-end - Docker, cloud (AWS), Hugging Face Spaces

## Featured Projects

### [parla](https://github.com/Mj-myhub/parla) - Evaluation-driven agentic English writing tutor
A LangGraph agent that gives English learners grammar feedback grounded in real rules, distinguishing verified corrections from unverified suggestions via a two-tier grounding check. Hybrid error detection (rules + spaCy + LLM), measured with ERRANT against hand-annotated learner writing.
**Tools:** LangGraph, LangChain, ChromaDB, spaCy, Groq (Llama), Docker, pytest + CI

### [findoc-rag](https://github.com/Mj-myhub/findoc-rag) - RAG over SEC 10-K filings
Answers financial questions grounded in real filings with citations, or honestly abstains when it can't find an answer. Hybrid BM25 + dense retrieval with RRF fusion and cross-encoder reranking, deployed via Docker to Hugging Face Spaces and AWS EC2, with a full ablation study of retrieval design choices.
**Tools:** sentence-transformers, ChromaDB, rank-bm25, pdfplumber, Groq, FastAPI, Gradio

### [multifaith](https://github.com/Mj-myhub/multifaith) - Multilingual faithfulness evaluation for RAG
A harness that checks whether hallucination/groundedness judges can actually be trusted outside English, with first-class support for Italian and Persian. Compares LLM-as-judge, NLI, and classifier-based scorers against human-labelled gold data, motivated in part by EU AI Act evaluation requirements.
**Tools:** Python, transformers, Cohen's kappa analysis, multilingual NLI

### [gpt2-language-acquisition](https://github.com/Mj-myhub/gpt2-language-acquisition) - Thesis project
Fine-tuned GPT-2 (117M-774M) on CHILDES child-directed speech to model aspects of language acquisition, including wh-questions, aux-less questions, and linguistic generalisation.
**Tools:** Python, Google Colab, GPT-2

## Interests

- Large Language Models (LLMs) & Agentic Systems
- Retrieval-Augmented Generation (RAG)
- Multilingual NLP Evaluation & Hallucination Detection
- Computational Linguistics & Psycholinguistics
- Language Acquisition Modelling
- Transformer Architectures

## Tech Stack

**Languages & Tools:** Python, Jupyter Notebook, Git, Docker

**LLM / Agentic:** LangGraph, LangChain, Groq (Llama), Hugging Face, prompt/agent evaluation

**Retrieval & RAG:** ChromaDB, BM25 (rank-bm25), cross-encoder reranking, sentence-transformers, FastAPI, Gradio, Streamlit

**ML / NLP:** PyTorch, TensorFlow, spaCy, NLTK, scikit-learn

**Deployment:** Docker, AWS (EC2), Hugging Face Spaces, GitHub Actions CI

## Background

I hold an M.Sc. in Language and Mind: Linguistics and Cognitive Studies from the University of Siena.

I'm based in Rome, Italy, and I speak English (C2), Italian (B2), and Persian (native).

## Get in touch

- LinkedIn
- Email: m.jeffrey2023@gmail.com
