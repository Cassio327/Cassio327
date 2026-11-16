# Generative AI Engineering — Additional Training

**Course:** [Formação Engenheiro de IA Generativa 2026: IA na Prática (Udemy)](https://www.udemy.com/course/formacao-engenheiro-de-ia-generativa-ia-na-pratica)

**Instructors:** Paulo Andrade and Rodrigo Macedo (as listed in the shared course summary).

**Curriculum scope:** approximately **64 hours**, **44 sections**, and **468 activities**, according to the course material provided. These are *course catalog figures*, not a claim about time spent on independent engineering projects or a separately verified certificate.

## Learning areas

This document summarizes **topics covered during training**, not a claim of professional mastery or production experience with every tool listed. For implemented and tested work, see [GovCheck AI](https://github.com/Cassio327/govcheck-ai), [FoodDemand AI](https://github.com/Cassio327/fooddemand-ai), and the [GitHub profile](../README.md).

| Area | Subjects covered |
| --- | --- |
| **Python and software foundations** | Python fundamentals and intermediate/advanced features; collections; functions; OOP, inheritance, polymorphism, composition; generators, iterators, decorators, regular expressions, async programming, type hints, modularity, files and environments; Git/GitHub and dependency management |
| **LLMs and prompt engineering** | Model behavior and limitations; tokens/context windows, temperature, provider selection by cost/latency/quality; system/user messages; few-shot prompts; reusable prompt templates; structured outputs; prompt refinement and evaluation |
| **Model providers and multimodal applications** | OpenAI/GPT, Gemini, Groq, Claude, Mistral, Cohere, Kimi, DeepSeek, Hugging Face; text and chatbot applications; conversational history; tool calling; images, DALL·E, Whisper transcription, text-to-speech, and multimodal assistants |
| **Agents and orchestration** | Chatbots versus workflows versus agents; tool use, routing, delegated specialized tasks, memory, failure handling, sequential/parallel/hierarchical execution, human oversight and guardrails |
| **LangChain, LangGraph, CrewAI, Agno** | LangChain chains, templates and tools; LangGraph nodes, edges, state, reducers, checkpoints, conditional branches, subgraphs, streaming, human-in-the-loop and agentic RAG; CrewAI tasks/crews and YAML configuration; Agno agents and tools |
| **RAG and document intelligence** | Ingestion, chunking, embeddings, vector databases, semantic retrieval, grounded answers, agentic RAG, Pinecone; retrieval/answer evaluation; LlamaIndex loaders, query engines, ReAct agents, external tools and document/data assistants |
| **MCP and AI-assisted development** | **Model Context Protocol** client/server concepts, standardized tool exposure and external-service integration; Claude Code, assisted planning/refactoring, tool safety, and AI-assisted development environments |
| **APIs and persistence** | HTTP methods, REST, JSON, authentication via API keys, request/response handling, failures, database connections, CRUD and integrating external services with agents |
| **Data and statistical methods** | NumPy; pandas; numerical/tabular data cleaning and transformations; descriptive statistics, dispersion, correlation, chi-square; EDA, missing values, outliers, visualizations and interpretation |
| **NLP, images and speech** | Tokenization, stopwords, stemming/lemmatization, sentiment and text classification, FAQ systems; Pillow image manipulation; OCR concepts; TTS, speech recognition and voice assistants |
| **Interfaces, automations, local models** | Streamlit and Gradio UI prototypes; Hugging Face Spaces; n8n and Langflow workflows, integrations and human approval; Ollama and LM Studio for local models |
| **Evaluation and responsible use** | Tests for LLM applications, output validation, grounding, hallucination risk, guardrails, constrained agent tools, error handling, privacy and human review |

## Connection to implemented portfolio projects

| Evidence from code | Where it is demonstrated |
| --- | --- |
| **LLMs, RAG, LangGraph, tool calling, provenance and review** | [GovCheck AI](https://github.com/Cassio327/govcheck-ai) — document analysis with hybrid retrieval, graph-based stages and page-level evidence |
| **Model training, temporal evaluation, API serving and artifacts** | [FoodDemand AI](https://github.com/Cassio327/fooddemand-ai) — reproducible demand forecasting, verified benchmark and [published Hugging Face artifact](https://huggingface.co/cassiohfs/fooddemand-ai) |
| **Backend/API engineering, authentication and CI** | [TaskFlow API](https://github.com/Cassio327/taskflow-api) |
| **Security, reliability, observability and regression testing** | [CourseSphere Security Hardening](https://github.com/Cassio327/coursesphere-security-hardening) |

**Evidence boundary:** Frameworks such as **CrewAI, Agno, LlamaIndex, Pinecone, n8n, Langflow, Gemini, or OpenAI multimodal APIs** appear in the *course syllabus*, but are **not presented here as deployed portfolio implementations** unless a specific repository demonstrates them. Completion certificates or credentials should only be linked when independently available and verified.
