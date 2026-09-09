# Deepthi Desharaju

I build agentic AI systems that do real work in the enterprise.
My focus is multi-step LLM agents, RAG pipelines, and MCP tool integrations — grounded in 10+ years of production data engineering.

---

### What I'm working on

At **Delta Dental**, I own vulnerability management analytics end to end — and I'm building the agentic layer on top of it.

**Shipped & in production:**
- **Power BI vulnerability dashboards** for Infrastructure and AppDev teams, fed by Python pipelines over the Nucleus Security API — cut weekly vulnerability status reporting from **~20 hours to under 10 minutes**
- **Risk Acceptance dashboard used by the CFO and Board of Directors** — eliminated ~20 hrs/week of manual consolidation and board-prep work

**Building now (agentic AI):**
- **Risk Advisory automation** — LangGraph agent orchestration over security policies, CVE bulletins, and SOPs to triage vulnerability impact and draft advisories, targeting the 30+ hrs/week the on-call team spends on manual analysis
- MCP servers exposing Snowflake, Nucleus Security, and ticketing to multiple LLM clients
- ChromaDB retrieval with **RAGAS evaluation** to keep quality honest; **LangSmith + Langfuse** tracing end to end

---

### What makes my AI work different

Most agentic systems fall apart at the data and retrieval layer, not the model layer.
That's the part I own end to end — SQL, Snowflake, dbt, Python, AWS, Power BI, ten-plus years of it.
And I treat evals and observability as part of the system, not an afterthought.

---

### Featured projects

AgentOrchestrator — Composable AI agent orchestration platform
Tri-layer registry (Tools → Skills → Sub-Agents) → dual orchestration modes (deterministic LangGraph + autonomous agentic) → MCP server hot-plugging → multi-layer memory (episodic · semantic · procedural with consolidation) → ambient intelligence with adaptive policy learning → A2A protocol routing.
854 tests, 48 milestones of spec-driven development with full acceptance ceremonies, auth + multi-tenancy, admin command center with complete run tracing.

CallLens — Multi-tenant B2B call analytics platform
100 real enterprise call transcripts → LangGraph pipeline (with human-in-the-loop gates) → Postgres with Row-Level Security → MCP server → role-aware answers in any LLM client (Claude Desktop, Codex).
JWT auth, 4 personas, role-scoped tools, idempotent SHA-256 ingestion, eval harness with regression guard, OTEL + Langfuse observability.

CodeShift Agent — Agentic code migration engine
LangGraph StateGraph analyzes public GitHub repos and generates evidence-validated Pydantic v1→v2 migration plans — AST-based static analysis, never executes repo code. V2 adds GitHub OAuth, Redis job queue, pgvector semantic memory, and cross-run delta detection — zero changes to the core graph.
327 tests, deterministic CI eval gate (6 scorers, no LLM judge), Prometheus + Grafana 11-panel dashboard.

---

### Stack

**AI / Agents** — LangChain · LangGraph · MCP · OpenAI · Anthropic Claude · Google Gemini · Google ADK
**Retrieval & Evals** — ChromaDB · Qdrant · FAISS · Azure AI Search · RAGAS · LLM-as-judge
**Observability** — LangSmith · Langfuse · OpenTelemetry
**Data** — Python · Snowflake · dbt · SQL · Kafka · AWS · Power BI · Tableau
**Infra** — FastAPI · Docker · Postgres · Redis

---

### Open to roles

Agentic AI Engineer · GenAI Engineer · Applied AI Engineer · AI Data Engineer
Based in the **Bay Area, CA**

[LinkedIn](https://www.linkedin.com/in/deepthidesharaju-125125103/) · desharajudeepthi@gmail.com
