## Sahil Chakraborty

AI Engineer. I build LLM systems that are evaluated, not demoed — and I publish the
numbers when they get worse.

**[sahilch.vercel.app](https://sahilch.vercel.app)** · [LinkedIn](https://linkedin.com/in/sahilch) · sahilch7359@gmail.com

---

### Shipped

**[DataChat](https://github.com/sahil7359/DataChat)** — agentic NL-to-SQL analytics.
LangGraph plan → retrieve → guardrail → execute → verify → explain. RAG-to-schema
grounding, AST SQL guardrail, read-only least-privilege role, MLflow tracing, and a
26-case golden set gating every PR.
[Live](https://data-chat-seven.vercel.app) · LangGraph, FastAPI, Postgres + pgvector, Redis, Next.js

**[Quorum](https://github.com/sahil7359/Quorum)** — supervisor agent for pull-request
review over the GitHub MCP server. Hybrid retrieval (dense + BM25 + RRF); a finding is
either cited to retrieved code or dropped. Nothing posts without human approval.
[Live](https://quorum-web.onrender.com) · LangGraph, MCP client + server, FastAPI, pgvector

**[ITR6-t2sql](https://github.com/sahil7359/ITR6-t2sql)** — plain-English querying of
Indian corporate tax filings. The engineering is the safety layer, not the SQL.
[Live](https://itr6-t2sql.streamlit.app) · 129 statutory line items · 2 independent safety gates · 55 tests

**[Electricity Forecasting](https://github.com/sahil7359/electricity_consumption_forecasting)** —
33 years of monthly US utility production. SARIMA at MASE 0.959, with the naive baseline
left in the results table so the model has to earn its complexity.
[Live](https://elecforecast.streamlit.app) · statsmodels, SARIMA, Holt-Winters

### Building

**Yardstick** — an agent that trains candidate models on tabular data and reports honestly
how good they are: automated leakage detection, every model scored against a trivial
baseline, and metric choice justified rather than defaulted.

### Currently

Platform & Data Engineer at TCS — enterprise GenAI framework, and billing-domain ETL on
AWS. Retrieval quality is a data quality problem; most of what breaks in a RAG system
breaks in the ingestion layer.
