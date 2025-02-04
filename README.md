# FinGPT: Real-Time LLM Financial Advisor 💰📊  

## Overview  
**FinGPT** is a production-ready LLM-powered financial advisor system that processes real-time market data using a **3-pipeline architecture**:  
- **Training Pipeline**: Fine-tunes a pretrained model on financial datasets using QLoRA.  
- **Streaming Pipeline**: Collects and embeds real-time stock and crypto data into a vector database.  
- **Inference Pipeline**: Retrieves context using **RAG**, generates financial insights, and serves responses via a REST API.  

## Features 🚀  
✅ **Retrieval-Augmented Generation (RAG)** for accurate financial insights.  
✅ **Real-time market data processing** via Alpaca API.  
✅ **Scalable deployment** using AWS, Docker, and GitHub Actions CI/CD.  
✅ **Serverless inference** on Beam for efficient API responses.  

## Tech Stack 🛠️  
- **LLM Fine-Tuning**: Hugging Face (QLoRA), Nous Hermes 2 Mistral 7B  
- **Experiment Tracking**: Weights & Biases (WandB)  
- **Data Streaming**: Alpaca API, ByteWax  
- **Vector Database**: Qdrant Cloud  
- **Deployment**: AWS EC2, Docker, GitHub Actions  

## Installation 🔧  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/sami10644/LLM-Powered-Financial-Decision-Assistant
cd FinGPT
pip install -r requirements.txt
