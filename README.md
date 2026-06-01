<div align="center">

<!-- Terminal-style banner -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=130&section=header&text=Joshua%20Mendoza&fontColor=00FF9C&fontSize=44&fontAlignY=42&desc=AI%20Software%20Engineer%20%7C%20LLM%20Systems%20%7C%20Agent%20Observability&descAlignY=74&descAlign=50" />

<br/>

<!-- Animated typing SVG -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=00FF9C&center=true&vCenter=true&width=900&lines=Building+production-grade+AI+systems;LLM+Agents+%7C+RAG+Evaluation+%7C+MCP+Tool+Tracing;FastAPI+%7C+PostgreSQL+%7C+Redis+%7C+Docker+%7C+AWS;Currently+building%3A+Agent+Flight+Recorder" />

<br/>

<img src="https://komarev.com/ghpvc/?username=joshuamendozaa&style=for-the-badge&color=00FF9C&label=PROFILE+VIEWS" />

</div>

---

<div align="center">

### `AI systems should be observable, testable, debuggable, and deployable.`

</div>

---

## `whoami`

I am an **AI Software Engineer** focused on building backend systems around LLMs, AI agents, RAG pipelines, tool-call tracing, guardrails, telemetry, and evaluation infrastructure.

My goal is to build AI systems that are not just demos, but systems that can be:

```txt
observed → evaluated → debugged → deployed → improved
```

---

## `currently_building`

### Agent Flight Recorder

An AI agent observability platform for tracing, evaluating, and debugging LLM agent behavior.

```txt
┌─ Agent Flight Recorder ─────────────────────────────────────┐
│ Status: Building                                            │
│ Focus: LLM agents · RAG evals · MCP traces · guardrails     │
│ Stack: Python · FastAPI · PostgreSQL · Redis · Docker · AWS │
│ Goal: Debuggable, production-grade AI systems               │
└─────────────────────────────────────────────────────────────┘
```

**Planned features**

- Trace prompts, responses, tool calls, latency, cost, and failures
- Evaluate RAG answers for faithfulness and retrieval quality
- Log MCP tool-call behavior
- Detect unsafe, low-confidence, or unsupported outputs
- Visualize agent behavior through a debugging dashboard
- Deploy with Docker and AWS

---

## `featured_projects`

### 1. AI Model Battle

Real-time LLM benchmarking platform where multiple models compete on standardized prompts and are scored live.

```txt
Prompt → Multiple LLMs → Judge Evaluation → Metrics → Live Leaderboard
```

**What it does**

- Runs parallel model responses using async FastAPI endpoints
- Streams live results through WebSockets
- Uses an LLM-as-a-Judge evaluation system inspired by MT-Bench-style scoring
- Scores responses across correctness, reasoning, completeness, conciseness, and coherence
- Runs local model inference through Ollama with models like DeepSeek, Llama, and Mistral
- Stores model metadata in PostgreSQL
- Stores benchmark metrics in InfluxDB
- Uses Redis caching to reduce leaderboard latency from ~150ms to under 1ms
- Containerized with Docker Compose
- Includes pytest testing and GitHub Actions CI/CD

**Stack**

<p align="center">
  <img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/WebSockets-0D1117?style=for-the-badge&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/InfluxDB-0D1117?style=for-the-badge&logo=influxdb&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Redis-0D1117?style=for-the-badge&logo=redis&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Docker%20Compose-0D1117?style=for-the-badge&logo=docker&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/pytest-0D1117?style=for-the-badge&logo=pytest&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Ollama-0D1117?style=for-the-badge&logo=ollama&logoColor=00FF9C" />
</p>

---

### 2. GPUScout

GPU diagnostics and telemetry service for monitoring GPU health and inference-readiness.

```txt
GPU → NVML / nvidia-smi → Telemetry → Backend Service → Diagnostics
```

**What it does**

- Captures real-time GPU telemetry
- Tracks driver, memory, temperature, and utilization metrics
- Uses NVML for GPU data collection
- Falls back to `nvidia-smi` for resilient metric collection
- Designed for varied GPU configurations
- Simulates inference-orchestration workflows

**Stack**

<p align="center">
  <img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/NVML-0D1117?style=for-the-badge&logo=nvidia&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/nvidia--smi-0D1117?style=for-the-badge&logo=nvidia&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Telemetry-0D1117?style=for-the-badge&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Diagnostics-0D1117?style=for-the-badge&logoColor=00FF9C" />
</p>

---

### 3. Agent Flight Recorder

AI observability platform for tracing and debugging agent behavior.

```txt
Agent Run → Tool Calls → Logs → Evals → Guardrails → Debug Dashboard
```

**What it is designed to do**

- Capture full AI agent execution traces
- Log model inputs, outputs, tool calls, errors, and latency
- Evaluate RAG answers and agent decisions
- Provide debugging visibility into black-box AI workflows
- Support production-style AI software engineering

**Stack**

<p align="center">
  <img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Redis-0D1117?style=for-the-badge&logo=redis&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonaws&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/OpenAI-0D1117?style=for-the-badge&logo=openai&logoColor=00FF9C" />
  <img src="https://img.shields.io/badge/MCP-0D1117?style=for-the-badge&logoColor=00FF9C" />
</p>

---

## `engineering_focus`

```txt
AI Software Engineering
├── LLM benchmarking
├── Agent observability
├── RAG evaluation
├── Tool-call tracing
├── Backend API design
├── Async systems
├── WebSocket streaming
├── Telemetry pipelines
├── Time-series metrics
├── Redis caching
├── Dockerized services
├── CI/CD pipelines
└── Production debugging
```

---

## `tech_stack`

<div align="center">

### Languages

<img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/C++-0D1117?style=for-the-badge&logo=cplusplus&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/C-0D1117?style=for-the-badge&logo=c&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Java-0D1117?style=for-the-badge&logo=openjdk&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/HTML%2FCSS-0D1117?style=for-the-badge&logo=html5&logoColor=00FF9C" />

### Backend / Infrastructure

<img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Node.js-0D1117?style=for-the-badge&logo=nodedotjs&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Express.js-0D1117?style=for-the-badge&logo=express&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Uvicorn-0D1117?style=for-the-badge&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Pydantic-0D1117?style=for-the-badge&logo=pydantic&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/SQLAlchemy-0D1117?style=for-the-badge&logo=sqlalchemy&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/REST%20APIs-0D1117?style=for-the-badge&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/WebSockets-0D1117?style=for-the-badge&logoColor=00FF9C" />

### Databases & Data

<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/MySQL-0D1117?style=for-the-badge&logo=mysql&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/MongoDB-0D1117?style=for-the-badge&logo=mongodb&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/InfluxDB-0D1117?style=for-the-badge&logo=influxdb&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Redis-0D1117?style=for-the-badge&logo=redis&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/pandas-0D1117?style=for-the-badge&logo=pandas&logoColor=00FF9C" />

### DevOps & Tools

<img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Docker%20Compose-0D1117?style=for-the-badge&logo=docker&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/GitHub%20Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/pytest-0D1117?style=for-the-badge&logo=pytest&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonaws&logoColor=00FF9C" />

### AI Development

<img src="https://img.shields.io/badge/OpenAI-0D1117?style=for-the-badge&logo=openai&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Ollama-0D1117?style=for-the-badge&logo=ollama&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/MCP-0D1117?style=for-the-badge&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Claude%20Code-0D1117?style=for-the-badge&logo=anthropic&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/GitHub%20Copilot-0D1117?style=for-the-badge&logo=githubcopilot&logoColor=00FF9C" />
<img src="https://img.shields.io/badge/Cursor-0D1117?style=for-the-badge&logoColor=00FF9C" />

</div>

---

## `system_design_notes`

```txt
What I like building:
  ├─ APIs that serve AI features
  ├─ dashboards that explain model behavior
  ├─ eval systems that measure output quality
  ├─ telemetry pipelines for infrastructure visibility
  ├─ tools that make AI agents easier to debug
  └─ backend systems that are reliable enough to deploy
```

---

## `current_signal`

```txt
> Building toward: AI Software Engineer
> Current project: Agent Flight Recorder
> Core stack: Python, FastAPI, PostgreSQL, Redis, Docker, AWS
> Strongest areas: backend systems, LLM evaluation, telemetry, observability
> Next focus: production deployment, RAG eval pipelines, MCP tracing, agent workflows
```

---

## `connect`

<div align="center">

<a href="https://github.com/joshuamendozaa">
  <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=00FF9C" />
</a>
<a href="https://linkedin.com/in/joshua-mendoza-1426742a6">
  <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF9C" />
</a>
<a href="mailto:jamendoza1002@gmail.com">
  <img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=00FF9C" />
</a>

</div>

---

<div align="center">

```txt
┌─────────────────────────────────────────────────────────────┐
│ Building AI systems that can be traced, tested, and trusted │
└─────────────────────────────────────────────────────────────┘
```

</div>
