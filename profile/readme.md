# Welcome to O2-Labz ⚡

**O2-Labz** is a software engineering group based out of Regina, SK for 2026-2027 Software Systems Engineering Capstone; in partnership with **SaskTel**, delivering open-source, vendor-neutral network automation for 5G.

**Members:**
Zana Osman
Hashir Owais

---

## Featured Project: Project Odin 🦅

**Project Odin** is an open-source implementation of the 3GPP **Network Data Analytics Function (NWDAF)** — the AI brain of the 5G core. Odin ingests control-plane telemetry from network functions, runs statistical and ML analytics, and notifies consumer network functions (PCF/OAM/SMF/AMF) to close the automation loop: predict problems, mitigate automatically, zero human intervention.

Built to 3GPP Release 18 and validated against SaskTel's multi-vendor 5G cloud, Odin proves that a third-party, vendor-neutral NWDAF can plug into a commercial core — escaping vendor lock-in and returning telemetry ownership to the operator.

```text
┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│ Producer NFs │ ──► │  ODIN (NWDAF)│ ──► │ Consumer NFs │
│ AMF/SMF/PCF  │     │ ingest → ML  │     │ PCF/OAM/SMF  │
│ OAM/UDM      │     │ → analytics  │     │ → enforce    │
└──────────────┘     └──────────────┘     └──────────────┘
   telemetry in        the brain           closed-loop action
```

## Repositories

| Repo | Purpose |
|---|---|
| [`odin-docs`](https://github.com/O2-Labz/odin-docs) | Project management (PMBOK artifacts), design analysis, solution architecture |
| `odin-nwdaf` | *(planned)* The NWDAF service itself (Rust) |
| `odin-loop` | *(planned)* PCF stand-in consumer + chaos harness |
| `odin-api` | *(planned)* Codegen + shared SBI types from 3GPP OpenAPI |
| `odin-deploy` | *(planned)* Operator-facing k8s deployment manifests |

## Kanban

All capstone work is tracked on the **Odin Kanban** board: https://github.com/orgs/O2-Labz/projects/4
