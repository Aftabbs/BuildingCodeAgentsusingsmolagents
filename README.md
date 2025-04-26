#  SmolAgents: Building Intelligent Code Agents

![image](https://github.com/user-attachments/assets/c9bd6195-6247-4531-bf89-5548fbdb0120)


This repository showcases a full-stack exploration of **SmolAgents**, focusing on building, securing, monitoring, and enhancing **autonomous code agents**. From basic code generation to deep research integrations using LLMs, this project is a hands-on dive into the evolving landscape of AI-driven software agents.

---

### Objectives

- ✅ Build **basic code agents** with SmolAgents.
- 🔐 Implement **secure and sandboxed environments** to run generated code safely.
- 📊 Integrate **OpenTelemetry (OTel)** for real-time monitoring and traceability.
- 📡 Evaluate and monitor agent performance with **Arize AI**.
- 🔎 Develop a **Deep Research Agent** using **Tavily Search API** + `gpt-4o-mini` for real-time context gathering.

---

##  Core Components

### 1. **Basic Code Agent**
- Uses SmolAgent architecture to interpret natural language instructions into Python code.
- Capable of writing and executing modular code snippets.
- Supports multiple iterations via feedback loop.

### 2. **Secure Execution Environment**
- Sandboxed code execution using isolated subprocesses.
- Protection against harmful code (e.g., file access, network calls).
- Error handling and traceback summaries for debugging.

### 3. **Monitoring with OpenTelemetry (OTel)**
- Real-time tracing of agent steps.
- Contextual logging for requests/responses.
- Export traces to visualization platforms (e.g., Jaeger, Zipkin).

### 4. **Model Evaluation with Arize AI**
- Tracks model performance (e.g., latency, error rate).
- Visualizes LLM behavior over time.
- Supports embedding tracking and drift detection.

### 5. **Deep Research Agent**
- Uses **Tavily API** to fetch curated search results for a given query.
- Enhances LLMs (OpenAI GPT-4o-mini) with up-to-date knowledge.
- Can write code with real-world references and citations.

---

## 🛠️ Tech Stack

| Tool / Library   | Purpose |
|------------------|---------|
| `smol-developer` | Core code agent framework |
| `openai`         | LLM completions & GPT-4o mini |
| `tavily`         | Real-time web search |
| `otel`           | Observability and tracing |
| `arize-ai`       | Model evaluation/monitoring |
| `pandas`         | Data manipulation |
| `numpy`          | Numerical computation |
| `pydantic`       | Data validation |
| `huggingface_hub`| HF model management |
| `hf_api`         | API interface for HF models |

---

##  Key Learnings

- SmolAgents provide a flexible abstraction over LLM-powered coding pipelines.
- Real-time observability via OTel + Arize AI is essential for debugging and auditing LLM agents.
- Plugging in external tools like Tavily enables agents to move from *static* to *dynamic* reasoning.


![image](https://github.com/user-attachments/assets/da5df22e-0daa-4439-a033-da3365f9a977)

![image](https://github.com/user-attachments/assets/8aa441a6-41e1-4e58-849c-0f0c9b2ccadf)

![image](https://github.com/user-attachments/assets/e289de7c-a6ec-4a61-90af-a70e0b0934b8)


## 📌 References

- [SmolAI GitHub](https://github.com/smol-ai)
- [OpenAI API Docs](https://platform.openai.com/docs)
- [Tavily API Docs](https://docs.tavily.com)
- [OpenTelemetry](https://opentelemetry.io/)
- [Arize AI](https://docs.arize.com/)

---

