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

##  Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
