<div align="center">

# Akhilesh Thokala

### AI Solutions Engineer | Cloud, Agentic Systems, RAG, and Enterprise Integration

I build practical AI systems that connect models to tools, data, guardrails, and business workflows.

[![Portfolio Focus](https://img.shields.io/badge/Portfolio-AI%20Solutions%20Engineering-1f6feb?style=for-the-badge)](#featured-portfolio)
[![Cloud](https://img.shields.io/badge/Cloud-GCP%20%7C%20Cloud%20Run%20%7C%20BigQuery-34a853?style=for-the-badge)](#technical-signal)
[![Agents](https://img.shields.io/badge/Agents-MCP%20%7C%20Tool%20Calling%20%7C%20Guardrails-8b5cf6?style=for-the-badge)](#featured-portfolio)

</div>

## What I Want Reviewers To See

I am positioning for Solutions Engineer / Customer Engineer roles where the job is not just to write code, but to turn ambiguous customer problems into working, credible technical demos.

My current portfolio focuses on:

- Agentic workflows with clear tool boundaries and human approval gates.
- RAG systems with semantic retrieval, source grounding, citations, and evals.
- GCP-style implementation patterns using BigQuery, Cloud Run, and Vertex AI / Gemini.
- Public-safe demos that use synthetic or public data instead of private customer data.

## Featured Portfolio

| Project | What It Demonstrates | Why It Matters |
|---|---|---|
| [retail-ops-agent-gcp](https://github.com/akhilesh12354/retail-ops-agent-gcp) | Retail operations agent with synthetic inventory data, BOPIS routing, ship-from-store routing, refusal guardrails, BigQuery adapter, Vertex AI / Gemini adapter, Cloud Run deployment notes, and 42 eval scenarios. | Shows how I would scope and prove a practical Google Cloud AI pilot for a retail customer. |
| [enterprise-rag-clinical-guidelines](https://github.com/akhilesh12354/enterprise-rag-clinical-guidelines) | RAG pipeline over public CMS policy PDFs with ChromaDB, semantic retrieval, source citations, MCP retrieval tools, and a transparent retrieval-speed benchmark. | Shows governed, source-grounded enterprise knowledge retrieval rather than a generic chatbot. |
| [mcp-ops-orchestrator](https://github.com/akhilesh12354/mcp-ops-orchestrator) | Multi-tool MCP orchestration with customer lookup, ticket creation, email drafting, structured logs, and a human-in-the-loop approval gate. | Shows how agent systems can be made operationally safe and auditable. |

## Technical Signal

| Area | Evidence In This Portfolio |
|---|---|
| Cloud architecture | Cloud Run deployment paths, BigQuery-shaped repositories, IAM notes, native GCP validation plans. |
| Agent systems | MCP stdio servers, LLM tool-calling boundaries, deterministic fallbacks, human approval gates. |
| Retrieval systems | PDF ingestion, embeddings, vector search, source citations, retrieval evals. |
| Evaluation | 42-case retail eval suite, retrieval hit-rate checks, benchmark fixtures, CI-backed tests. |
| Enterprise readiness | Synthetic data, no secrets in repos, refusal guardrails, public-safety notes, least-privilege deployment guidance. |

## How To Evaluate The Work

If you only have five minutes:

1. Open [retail-ops-agent-gcp](https://github.com/akhilesh12354/retail-ops-agent-gcp) and scan the README claim mapping.
2. Check `evals/eval_cases.json` for the 42 retail scenarios.
3. Open [enterprise-rag-clinical-guidelines](https://github.com/akhilesh12354/enterprise-rag-clinical-guidelines) and inspect the MCP server plus benchmark docs.
4. Open [mcp-ops-orchestrator](https://github.com/akhilesh12354/mcp-ops-orchestrator) and review the MCP process boundaries and HITL design.

If you want to run something locally:

```bash
git clone https://github.com/akhilesh12354/retail-ops-agent-gcp.git
cd retail-ops-agent-gcp
make test
make eval
make demo
```

## Current Build Direction

The next step is native GCP validation:

- Deploy the retail agent to Cloud Run.
- Seed synthetic inventory/order/capacity data into BigQuery.
- Enable Vertex AI / Gemini tool-call planning behind an environment flag.
- Smoke test the same eval prompts against the deployed endpoint.

The local demos are already public-safe and deterministic; the cloud pass is about proving the same architecture in a managed GCP environment.

## Principles I Build With

- Make the demo runnable before making it fancy.
- Keep claims testable, cited, and easy to inspect.
- Use synthetic/public data for portfolio work.
- Treat evals, guardrails, and deployment notes as part of the product.
- Design for the conversation a customer engineer or solutions engineer actually has with a buyer.

## Contact

- GitHub: [akhilesh12354](https://github.com/akhilesh12354)
- Portfolio focus: AI solutions engineering, cloud architecture, agentic workflows, and enterprise integration.

