# Incident RAG Python

This project demonstrates a local Retrieval-Augmented Generation workflow for incident management.

It loads historical incident reports, creates OpenAI embeddings, stores vectors in a local FAISS index, retrieves similar incidents, and generates an AI-powered triage recommendation.

## Features

- Parse markdown incident reports
- Generate OpenAI embeddings
- Build a local FAISS vector index
- Search similar historical incidents
- Generate triage recommendations using OpenAI
- Works directly in Google Colab

## Install

```bash
pip install -r requirements.txt