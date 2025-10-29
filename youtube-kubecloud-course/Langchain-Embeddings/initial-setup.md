# Mission: Build TechDocs Semantic Search Engine

The Problem at TechDocs Inc.

Your company's documentation portal gets 10,000 searches daily with a 60% failure rate! Users search "reset password" but docs say "password recovery process" - keywords don't match meaning.
Your Mission: Semantic Search

Build a search engine that understands MEANING, not just keywords:

    Before: "work from home" finds nothing
    After: "work from home" finds "remote work policy"
    Result: Search success jumps to 95%!

🚀 No AI generation yet - just incredibly smart search using embeddings!

## 🛠️ Environment Setup

### 📦 Installing Vector Search Libraries

What Gets Installed:

    ✅ sentence-transformers - Embedding models from HuggingFace
    ✅ langchain - Abstraction framework
    ✅ langchain-community - Vector store integrations
    ✅ langchain-huggingface - HuggingFace embeddings integration
    ✅ chromadb - Production vector database
    ✅ numpy - Vector mathematics

🤖 Models (auto-download on first use):
• all-mpnet-base-v2 (768 dimensions - high accuracy)
• all-MiniLM-L6-v2 (384 dimensions - fast)

### 🚀 Run Setup Commands
cd /root && python3 -m venv venv && source venv/bin/activate
pip install sentence-transformers langchain langchain-community langchain-huggingface chromadb numpy

### ✅ Verify Installation
python3 /root/code/verify_environment.py

Check if environment verification is completed
