# LangGraph Basics: Build Stateful AI Workflows

## What is LangGraph?

LangGraph is a framework for building stateful, multi-step AI workflows using graphs. Unlike simple LLM chains, LangGraph gives you explicit control over how data flows through your application, enabling complex decision-making, loops, and conditional routing.

## Master the Fundamentals Step by Step

Learn LangGraph progressively - from basic imports to building a complete research assistant with multiple tools.

Your 7-Step Learning Journey
1️⃣ Imports - Foundation setup

2️⃣ Nodes - State functions

3️⃣ Edges - Connect nodes

4️⃣ Complete Flow - Multi-step

5️⃣ Routing -  Conditionals

6️⃣ Calculator - LLM tool

7️⃣ Research Agent - Complete AI

> Build progressively: Start with imports → End with a complete research assistant!

![](./langgraph-steps.png)

# Environment Setup

Installing LangGraph

What Gets Installed:

    langgraph - Stateful graph framework
    langchain - Core LLM abstractions
    langchain-openai - OpenAI integration
    duckduckgo-search - Web search tool

> Pre-configured: OpenAI proxy at OPENAI_API_BASE

Run Setup
```
cd /root && source /root/venv/bin/activate
pip install langgraph langchain langchain-openai duckduckgo-search
```

Verify
`python3 /root/code/verify_environment.py`