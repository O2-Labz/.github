# Welcome to O2-Labz

**O2-Labz** is a software engineering group based in Regina, SK, working on our 2026–2027 Software Systems Engineering capstone **in partnership with SaskTel** — building an AI brain for their 5G network core.

**The team:**
- **Hashir Owais** — Project Manager / Technical Lead
- **Zana Osman** — Full Stack Software Engineer

---

## Featured Project: Project Odin

**Project Odin** is the AI brain of a 5G core network. Think of it like a fitness tracker for the network: it **watches**, it **learns** what healthy looks like, and it **predicts** problems before customers ever feel them — then tells the network's own systems to fix it, with no human in the loop.

Odin is being built as a scoped MVP for SaskTel: we ship one complete closed loop (sense → predict → notify → act) with measured evidence, so SaskTel can evaluate it and decide whether to keep building their own network intelligence or buy a vendor solution. Whatever they pick, the network data and the models stay theirs — no lock-in, ever.

```text
┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│   Network    │ ──► │     ODIN     │ ──► │   Network    │
│  (senses)    │     │  (the brain) │     │  (the hands) │
│ phones,      │     │ watch → learn│     │ policy,      │
│ sessions,    │     │ → predict    │     │ quarantine,  │
│ load metrics │     │              │     │ scale out    │
└──────────────┘     └──────────────┘     └──────────────┘
   signals in         no human needed      action out
```

## Repositories

| Repo | Purpose |
|---|---|
| [`odin-docs`](https://github.com/O2-Labz/odin-docs) | Project management, design analysis, solution architecture |
| `odin-brain` | *(planned)* The Odin service itself — ingestion, models, predictions (Rust) |
| `odin-loop` | *(planned)* The closed-loop consumer stand-in + failure-injection harness |
| `odin-api` | *(planned)* Codegen + shared API types from the 3GPP OpenAPI definitions |
| `odin-deploy` | *(planned)* Kubernetes deployment manifests |

## Kanban

All capstone work is tracked on the **Odin Kanban** board: https://github.com/orgs/O2-Labz/projects/4
