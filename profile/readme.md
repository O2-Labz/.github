# Welcome to O2-Labz ⚡

**O2-Labz** is an engineering research lab developing next-generation core network tooling, automated analytics, and infrastructure intelligence platforms.

---

## Featured Project: Project Odin 🦅

**Project Odin** is an automated network intelligence and predictive analytics platform implementing a scoped 3GPP **Network Data Analytics Function (NWDAF)**. Built for real-time visibility into 5G Core (5GC) infrastructure, Odin ingests high-volume telemetry, processes network events, and provides actionable operational foresight.

```text
                    ┌─────────────────────────┐
                    │   5G Core Infrastructure│
                    └────────────┬────────────┘
                                 │ Telemetry
                                 ▼
                    ┌─────────────────────────┐
                    │  odin-collector (Muninn)│
                    └────────────┬────────────┘
                                 │ Ingest
                                 ▼
                    ┌─────────────────────────┐
                    │     odin-core (Huginn)  │
                    └────────────┬────────────┘
                                 │ Insights
                                 ▼
                    ┌─────────────────────────┐
                    │   odin-api (Gateway)    │
                    └─────────────────────────┘
