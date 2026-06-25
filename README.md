<div align="center">

# Akhilesh Thokala

### Cloud & AI Solutions Engineer

I turn ambiguous enterprise problems into runnable technical proofs using GCP, agentic AI, retrieval systems, APIs, and integration architecture.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akhileshthokala)
[![GitHub](https://img.shields.io/badge/GitHub-Projects-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/akhileshthokala?tab=repositories)

</div>

## Start Here

### [Retail Operations Agent on GCP](https://github.com/akhileshthokala/retail-ops-agent-gcp)

A public-safe retail operations agent that detects phantom inventory, recommends BOPIS and ship-from-store routing, cites its evidence, and refuses unsupported requests.

**Built with:** Python, FastAPI, BigQuery and Vertex AI adapters, Cloud Run deployment tooling, deterministic guardrails, and a 42-scenario evaluation suite.

[Architecture](https://github.com/akhileshthokala/retail-ops-agent-gcp/blob/main/docs/architecture.md) ·
[Evaluation methodology](https://github.com/akhileshthokala/retail-ops-agent-gcp/blob/main/docs/eval-methodology.md) ·
[Demo script](https://github.com/akhileshthokala/retail-ops-agent-gcp/blob/main/docs/demo-script.md) ·
[Design decisions](https://github.com/akhileshthokala/retail-ops-agent-gcp/blob/main/docs/design-decisions.md)

## More Applied AI Work

| Project | What it proves |
|---|---|
| [Enterprise RAG Clinical Guidelines](https://github.com/akhileshthokala/enterprise-rag-clinical-guidelines) | Source-grounded retrieval over public CMS policy documents with ChromaDB, citations, MCP tools, retrieval evals, and a transparent benchmark. |
| [MCP Ops Orchestrator](https://github.com/akhileshthokala/mcp-ops-orchestrator) | Bounded multi-tool orchestration with customer lookup, ticket creation, email drafting, structured audit logs, and human approval before consequential actions. |

## What I Bring

- **Customer-to-architecture translation:** turn discovery questions and business constraints into testable solution designs.
- **Applied AI engineering:** connect models to tools and enterprise data with citations, evals, guardrails, and human approval.
- **Cloud implementation judgment:** design for Cloud Run, BigQuery, Vertex AI, IAM boundaries, observability, and operational handoff.
- **Enterprise integration depth:** work across APIs, messaging, workflow orchestration, platform modernization, and distributed systems.

## Five-Minute Review Path

1. Read the [retail agent claim map](https://github.com/akhileshthokala/retail-ops-agent-gcp#resume-claim-mapping) to see what is implemented, simulated, and planned.
2. Inspect the [42 evaluation cases](https://github.com/akhileshthokala/retail-ops-agent-gcp/blob/main/evals/eval_cases.json) covering routing, grounding, and refusal behavior.
3. Compare the [RAG retrieval boundary](https://github.com/akhileshthokala/enterprise-rag-clinical-guidelines/blob/main/src/mcp_server.py) with the [MCP approval boundary](https://github.com/akhileshthokala/mcp-ops-orchestrator/blob/main/src/orchestrator.py).

Run the flagship project locally:

```bash
git clone https://github.com/akhileshthokala/retail-ops-agent-gcp.git
cd retail-ops-agent-gcp
make test
make eval
make demo
```

## Engineering Principles

- Make the demo runnable before making it fancy.
- Keep claims testable and easy to inspect.
- Use synthetic or public data in portfolio work.
- Treat evaluation, safety, and deployment guidance as product features.
- Document the line between implemented behavior and production hardening.

## Let’s Connect

I am interested in Customer Engineer, Solutions Engineer, and cloud architecture roles where technical depth supports real customer outcomes.

[Connect on LinkedIn](https://www.linkedin.com/in/akhileshthokala) or explore [all repositories](https://github.com/akhileshthokala?tab=repositories).
