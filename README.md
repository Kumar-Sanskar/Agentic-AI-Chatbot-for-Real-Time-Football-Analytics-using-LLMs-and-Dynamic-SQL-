# Agentic-AI-Chatbot-for-Real-Time-Football-Analytics-using-LLMs-and-Dynamic-SQL-
                        ┌────────────────────────────┐
                        │     User Interface Layer    │
                        │ ────────────────────────── │
                        │ • Chatbot (LangChain agent)│
                        └────────────┬───────────────┘
                                     ↓
                        ┌────────────────────────────┐
                        │       LLM & RAG Layer       │
                        │ ────────────────────────── │
                        │ • LangChain                │
                        │ • NVIDIA AI Endpoints      │
                        │ • Retrieval-Augmented Gen  │
                        └────────────┬───────────────┘
                                     ↓
                        ┌────────────────────────────┐
                        │     Agent Orchestration     │
                        │ ────────────────────────── │
                        │ • LangGraph Modular Agents │
                        │   - Entity Extraction      │
                        │   - ID Resolution          │
                        │   - SQL Generation         │
                        └────────────┬───────────────┘
                                     ↓
                        ┌────────────────────────────┐
                        │     Data Access & Matching  │
                        │ ────────────────────────── │
                        │ • RapidFuzz (Fuzzy Match)  │
                        │ • MySQL (Football Schema)  │
                        └────────────┬───────────────┘
                                     ↓
                        ┌────────────────────────────┐
                        │     Data Storage & ETL      │
                        │ ────────────────────────── │
                        │ • Real-time Football APIs  │
                        │ • AWS S3 (raw storage)     │
                        │ • MySQL (structured layer) │
                        └────────────┬───────────────┘
                                     ↓
                        ┌────────────────────────────┐
                        │   Query Execution & Output  │
                        │ ────────────────────────── │
                        │ • mysql-connector-python   │
                        │ • Dynamic SQL Engine       │
                        │ • Result Formatter         │
                        └────────────────────────────┘
