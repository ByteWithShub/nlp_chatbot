NLP-Based Question Answering System x World War

This project implements a domain-specific Question Answering (QA) system using transformer-based models.
It includes web scraping for dataset creation, semantic search, retrieval-augmented generation (RAG) techniques, and a Gradio-based UI for interactive querying.

Project Structure
- Web Scraping: Collects textual data from various online sources.
- Model Building: Fine-tunes and evaluates multiple transformer models (DistilBERT, RoBERTa + SentenceTransformer) for QA tasks.
- Tuning: Experiments with chunk size and confidence threshold to optimize retrieval quality.
- Final Model: Selects and deploys the best-performing model based on performance metrics.
- UI Deployment: Uses Gradio to create a user-friendly web interface for the QA system.

Models Used
- DistilBERT (for baseline QA performance)
- RoBERTa + Sentence-BERT (for semantic embedding and improved retrieval)

Key Features
- Domain-specific: Tailored dataset created via scraping.
- Multiple Model Comparison: Evaluate two strong architectures for QA.
- Confidence Threshold Tuning: Better control over answer quality.
- Interactive Web App: Quickly test the QA model using an intuitive Gradio interface.

||  "The world must know what happened and never forget." — Dwight D. Eisenhower 
