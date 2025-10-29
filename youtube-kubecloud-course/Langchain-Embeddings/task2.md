# ✂️ Smart Document Chunking

📄 Why Chunk Documents?

Large documents must be split into smaller pieces for embedding. But we need to be smart about it!
🔄 The Overlap Strategy

Chunk with overlap preserves context:

Document: [=========================================]
Chunk 1:  [==========]
Chunk 2:       [==========]
Chunk 3:            [==========]
          ^^^^ Overlap preserves context!

📊 Optimal Settings

    Chunk size: 500 characters (balanced)
    Overlap: 100 characters (20%)
    Result: 40% better retrieval accuracy!

💡 LangChain's RecursiveCharacterTextSplitter handles this intelligently, respecting sentence boundaries!

💡 Remember: Overlap preserves context between chunks!

>>>>  pip install langchain-text-splitters