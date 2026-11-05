# LangChain & LangGraph — AI Agents, Agentic RAG & MCP 🦜🔗

**My notes and code while learning to build real-world AI agents with LangChain and LangGraph (Python, v1.0+).**

Created by [Hayk Sahakyan](https://github.com/HaykSahakyan11). Each lesson lives on its own branch, one commit
per step, so you can check out any commit to see the project at that point.

![LangChain Logo](static/LangChain_OSS%20Lockup_light.png)
![LangGraph Logo](static/LangGraph_OSS%20Lockup_light.png)

License: [Apache 2.0](LICENSE)

## What's in this repo

| Branch | Topic |
|---|---|
| [`project/hellow-world`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/hellow-world) | First chain: prompt template + a local/cloud chat model |
| [`project/search-agent`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/search-agent) | Search agents with `create_agent`, custom tools, Tavily, structured outputs |
| [`project/agents-under-the-hood`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/agents-under-the-hood) | The same agent built three ways, peeling back each layer of abstraction |
| [`project/rag-gist`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/rag-gist) | Retrieval-augmented generation: ingestion, naive RAG, LCEL retrieval chain |
| [`project/agent-harnesses`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/agent-harnesses) | Turning a model into a deep agent with LangChain Deep Agents |
| [`project/system-one-models`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/system-one-models) | Jev (TypeSafe): calibrated harness decisions, model routing, auto-mode tool gating |
| [`project/agent-middleware`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/agent-middleware) | Agent middleware: summarization, guardrails, human-in-the-loop, runtime context |
| [`project/evaluating-jev`](https://github.com/HaykSahakyan11/Langchain_tutorial/tree/project/evaluating-jev) | Evaluating Jev with LangSmith: gold sets, calibration, cost-based thresholds |

## Getting started

```bash
git clone https://github.com/HaykSahakyan11/Langchain_tutorial.git
cd Langchain_tutorial
git checkout project/<branch-name>
uv sync
uv run python <script>.py
```

Each branch's own README has the exact setup and run steps for that lesson — start there.

### Prerequisites

- Python 3.11+ and [`uv`](https://docs.astral.sh/uv/)
- Access to an LLM (Ollama locally, or a cloud provider like OpenAI / Anthropic)
- Per-branch API keys as documented in that branch's README / `.env.example`

## Credits

Code and notes written while taking [Eden Marco](https://github.com/emarco177)'s *LangChain & LangGraph:
AI Agents, Agentic RAG & MCP* course. Big thanks to the **LangChain / LangGraph** team for their
[documentation and tutorials](https://langchain-ai.github.io/langgraph/tutorials/introduction/).

---

### 🔗 Connect with me

- LinkedIn: [hayk-sahakyan-021471138](https://www.linkedin.com/in/hayk-sahakyan-021471138)
- GitHub: [@HaykSahakyan11](https://github.com/HaykSahakyan11)
