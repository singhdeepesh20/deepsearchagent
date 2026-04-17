<div align="center">

# DeepSearch Agent

### Intelligent Multi-Source AI Research & Search System

</div>

---

## Overview

**DeepSearch Agent** is an AI-powered research assistant that combines **multi-source information retrieval** with **LLM-based reasoning** to deliver contextual and insightful answer.

Built using **LangChain Agents** and **Groq’s high-performance LLMs**, the system integrates academic and web search tools such as **Arxiv, Wikipedia, and DuckDuckGo** into a unified conversational interface.

It transforms traditional search into an **intelligent research workflow**.

---

## Key Features

* 🔎 **Multi-Source Search** → Arxiv, Wikipedia, and DuckDuckGo integration
* 🧠 **Agentic Reasoning** → LangChain Zero-Shot ReAct agent for tool selection
* ⚡ **Low-Latency LLM** → Groq-powered fast inference (LLaMA models)
* 💬 **Interactive Chat UI** → Streamlit-based conversational interface
* 🎨 **Enhanced UX** → Styled chat bubbles, background UI, loading states
* 🔐 **Secure API Handling** → User-provided Groq API key via sidebar

---

## System Architecture

```
User Query
     ↓
LangChain Agent (ReAct)
     ↓
Tool Selection
 ┌───────────────┬───────────────┬───────────────┐
 │   Arxiv API   │  Wikipedia    │ DuckDuckGo    │
 └───────────────┴───────────────┴───────────────┘
     ↓
Context Aggregation
     ↓
Groq LLM (LLaMA3)
     ↓
Final Answer (Contextual + Synthesized)
```

---

## Tech Stack

* **Frontend**: Streamlit
* **Framework**: LangChain
* **LLM**: Groq API (LLaMA3)
* **Search Tools**:

  * Arxiv API (research papers)
  * Wikipedia API (knowledge base)
  * DuckDuckGo API (web search)

---

## Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/deepsearch-ai-agent.git
cd deepsearch-ai-agent
```

### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate         # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Application

```bash
streamlit run app.py
```

---

## Usage

1. Enter your **Groq API Key** in the sidebar
2. Ask any research question
3. The agent will:

   * Select appropriate tools
   * Retrieve relevant information
   * Generate a contextual answer

---

## Engineering Highlights

### Agentic AI Design

* Uses **ReAct (Reasoning + Acting)** paradigm
* Dynamically selects tools based on query

### Multi-Source Retrieval

* Combines academic + general web sources
* Improves answer quality and coverage

### Real-Time Reasoning

* LLM synthesizes information into coherent insights

---

## Use Cases

* 📚 Academic Research Assistance
* 🌐 Intelligent Web Search
* 🧠 Knowledge Exploration
* 🧑‍💻 Developer Research Tool

---

## Future Enhancements

* Multi-document memory
* RAG-based persistent knowledge store
* Advanced ranking (MMR / hybrid search)
* Model selection (Mixtral, Gemma, LLaMA variants)
* Deployment via Docker / Cloud

---

## What This Project Demonstrates

* Agent-based AI system design
* Integration of LLMs with external tools
* Multi-source information retrieval
* Building real-world AI applications with UI

---

## License

This project is licensed under the MIT License.

---

## Author

**Deepesh Singh**
AI & Agentic Systems Engineer | Building Intelligent Systems

---

<div align="center">

### "From search to intelligence — redefining how we explore knowledge."

</div>

