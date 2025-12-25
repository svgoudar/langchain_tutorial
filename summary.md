
## 1. Core LLM Abstractions

* LLMs
* Chat Models
* Model Providers (OpenAI, Anthropic, Ollama, Hugging Face)
* Prompt Templates
* Output Parsers
* Runnable Interface
* LCEL (LangChain Expression Language)
* Model Parameters (temperature, top_p, max_tokens)

---

## 2. Prompt Engineering

* PromptTemplate
* ChatPromptTemplate
* System / Human / AI Messages
* Few-shot Prompting
* Chain-of-Thought (CoT)
* Self-Consistency
* Instruction Prompting
* Structured Output Prompts
* Guardrails (format enforcement)

---

## 3. Chains

* LLMChain
* SequentialChain
* SimpleSequentialChain
* RouterChain
* Map-Reduce Chains
* Refine Chain
* Stuff Chain
* Transform Chain
* RetrievalQA Chain
* ConversationalRetrievalChain

---

## 4. Retrieval-Augmented Generation (RAG)

* Document Loaders
* Text Splitters (chunking)
* Chunk Overlap
* Embeddings
* Vector Stores
* Similarity Search
* MMR (Max Marginal Relevance)
* Hybrid Search
* Re-ranking
* Context Window Management
* Source Attribution

---

## Metrics


## 5. Agents

* Tool Calling
* ReAct Agents
* OpenAI Tools Agent
* Conversational Agents
* Multi-Tool Agents
* Function Calling
* Agent Scratchpad
* Agent Executor
* Agent Memory
* Planning vs Execution Agents

---

## 6. Tools

* Custom Tools
* Structured Tools
* Tool Schemas (JSON Schema)
* API Tools
* Database Tools
* File System Tools
* Web Search Tools
* MCP Tool Adapters

---

## 7. Memory

* ConversationBufferMemory
* ConversationSummaryMemory
* ConversationBufferWindowMemory
* VectorStore-backed Memory
* Entity Memory
* Session-based Memory
* Long-term vs Short-term Memory

---

## 8. LangChain Expression Language (LCEL)

* RunnablePassthrough
* RunnableLambda
* RunnableParallel
* RunnableSequence
* Streaming Runnables
* Batch Execution
* Async Execution
* Retry & Fallbacks

---

## 9. Streaming & Callbacks

* Token Streaming
* Callback Handlers
* Tracing
* Logging
* Observability Hooks
* Cost Tracking
* Latency Tracking

---

## 10. Evaluation & Testing

* LLM Evaluation
* RAG Evaluation
* Faithfulness
* Relevance
* Answer Correctness
* Synthetic Data Generation
* Regression Testing
* Prompt Versioning

---

## 11. Data Ingestion & Processing

* PDF / CSV / HTML Loaders
* Web Scraping
* API-based Loaders
* Data Cleaning
* Metadata Enrichment
* Document Versioning
* Incremental Ingestion
* CDC-style Updates

---

## 12. Caching & Performance

* Prompt Caching
* LLM Response Caching
* Embedding Caching
* Redis Cache
* In-Memory Cache
* Cache Invalidation
* Rate Limiting

---

## 13. Security & Safety

* Prompt Injection Detection
* Input Sanitization
* Output Validation
* Content Filtering
* Secrets Management
* Role-based Access

---

## 14. Deployment & Integration

* FastAPI Integration
* Gradio / Streamlit UI
* Background Tasks
* Async Workers
* Server-Sent Events (SSE)
* WebSockets
* Load Balancing
* Horizontal Scaling

---

## 15. Interoperability

* LangGraph Integration
* LlamaIndex Integration
* MCP Integration
* External Vector DBs
* Cloud Services (AWS, GCP, Azure)

---

## 16. Production & Ops

* Config Management
* Environment Separation
* CI/CD for Prompts
* Versioned Pipelines
* Rollbacks
* Monitoring & Alerts
* Cost Optimization

---

## 17. Advanced / Emerging Concepts

* Agentic RAG
* Context-Aware RAG
* Hierarchical Agents
* Self-Reflection
* Tool Re-ranking
* Online Learning from Feedback
* Multi-Modal Chains
