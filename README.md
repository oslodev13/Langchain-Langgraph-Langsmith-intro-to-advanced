# LangChain · LangGraph · LangSmith — Intro to Advanced

A hands-on learning repository for building, orchestrating, and observing LLM applications using the LangChain ecosystem. It progresses from fundamentals to advanced, production-oriented patterns.

## Overview

| Tool | Purpose |
| --- | --- |
| **LangChain** | Compose LLMs with prompts, tools, retrievers, and chains. |
| **LangGraph** | Build stateful, multi-step, and multi-agent workflows as graphs. |
| **LangSmith** | Trace, debug, evaluate, and monitor your LLM applications. |

## Learning Path

1. **Intro** — LLM calls, prompt templates, output parsers, and simple chains.
2. **Intermediate** — Retrieval-Augmented Generation (RAG), memory, and tool calling.
3. **Advanced** — Agents, LangGraph state machines, multi-agent orchestration, and evaluation with LangSmith.

## Prerequisites

- Python 3.10+
- An LLM provider API key (e.g. OpenAI, Anthropic, or a local model)
- A [LangSmith](https://smith.langchain.com/) account (optional, for tracing)

## Setup

```bash
# Clone the repository
git clone https://github.com/<your-username>/Langchain-Langgraph-Langsmith-intro-to-advanced.git
cd Langchain-Langgraph-Langsmith-intro-to-advanced

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate        # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Configuration

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_key
LANGCHAIN_API_KEY=your_langsmith_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=intro-to-advanced
```

## Project Structure

```
.
├── 01-intro/           # Basic chains, prompts, and output parsers
├── 02-intermediate/    # RAG, memory, and tool calling
├── 03-advanced/        # Agents, LangGraph, and multi-agent systems
├── requirements.txt    # Python dependencies
└── README.md
```

## Usage

```bash
# Run an example
python 01-intro/hello_langchain.py
```

## Resources

- [LangChain Docs](https://python.langchain.com/)
- [LangGraph Docs](https://langchain-ai.github.io/langgraph/)
- [LangSmith Docs](https://docs.smith.langchain.com/)

## License

This project is licensed under the MIT License.
