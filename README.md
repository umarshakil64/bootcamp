#  Agentic Controller for Multi-Tool Query Handling

 Overview
This project implements a **lightweight agent** capable of decomposing complex queries into steps and dynamically selecting the right tool to answer them.  
The controller agent routes tasks to different tools such as **web search, calculator, document Q&A (RAG), and reasoning models**, showcasing multi-step reasoning across APIs.

-

##  Features
- Controller Agent – Parses user queries and selects the appropriate tool.
- Integrated Tools:
  -  Web Search (Tavily API)  
  -  Calculator (Python execution in Colab)  
  -  Document Q&A using **Retrieval-Augmented Generation (RAG)** with FAISS + embeddings  
  -  Reasoning Model (GSM8k fine-tuned model; experimental)  

---

https://colab.research.google.com/drive/1ixWqbOAyT-sY2RlU0hfeB26TQdlQpY_j#scrollTo=vMvLxnL7mba0


cp config.example.json config.json
{
  "TAVILY_API_KEY": "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",
  "GROQ_API_KEY": "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"
}

##  Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
