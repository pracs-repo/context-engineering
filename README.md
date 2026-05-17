# Context Engineering: Practical Guide
## Use Case: Customer Support AI Agent

A production-ready implementation of all 6 context engineering pillars using Python + OpenAI.
See each file for step-by-step implementation with inline explanations.

## Project Structure
```
context-engineering-guide/
├── README.md                    ← You are here
├── requirements.txt             ← Dependencies
├── agent/
│   ├── system_prompt.py        ← Step 1: System prompt design
│   ├── tools.py                ← Step 2: Tool definitions
│   ├── context_manager.py      ← Step 3: Context window management
│   ├── rag.py                  ← Step 4: RAG / external resources
│   ├── agent_loop.py           ← Step 5: Agent loop & reasoning
│   └── safety.py               ← Step 6: Safety & output validation
├── utils/
│   └── token_counter.py        ← Token budget tracking
├── data/
│   └── knowledge_base.py       ← Sample KB for the support agent
└── main.py                     ← Full working demo
```

## Quick Start
```bash
pip install -r requirements.txt
export OPENAI_API_KEY="your-key-here"
python main.py
```
