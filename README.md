<div align="center">

# Mohammed Al Assad

### Software Engineer · Backend · Distributed Systems · AI

I build systems where **reliability, execution, and data flow** matter — from APIs and durable background jobs to local-first ML infrastructure.

`Java` · `Spring Boot` · `Python` · `TypeScript` · `PostgreSQL` · `React` · `Docker`

</div>

---

### What I like building

```text
request → API → durable state → async execution → recovery → observable result
```

I’m especially interested in the parts of software that become important once the happy path stops being enough:

- durable jobs, retries, leases, heartbeats, and idempotency
- backend APIs and service boundaries
- concurrency and failure recovery
- data-intensive applications and ML infrastructure
- local-first software and reproducible execution
- developer tooling that makes complex systems easier to operate

---

## Selected engineering work

<table>
<tr>
<td width="50%" valign="top">

### Asyncra
**Durable background job orchestration**

A Postgres-backed execution system built around reliable asynchronous work rather than in-process background tasks.

**Highlights**
- retries and stale-lease recovery
- worker heartbeats and placement
- idempotency / side-effect fencing
- SSE logs and operator visibility
- TypeScript SDK for producers and workers

`Spring Boot` `PostgreSQL` `TypeScript` `React`

</td>
<td width="50%" valign="top">

### AtlasML
**Local-first AutoML platform**

A desktop ML system that separates product state, orchestration, and bounded model execution across clear runtime boundaries.

**Highlights**
- Electron + React desktop app
- Spring Boot control plane
- PostgreSQL authoritative state
- Python / XGBoost execution worker
- model evaluation, prediction, lineage, monitoring

`Java` `Python` `React` `Electron` `PostgreSQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ConUMaps
**Mobile campus navigation & planning**

A React Native campus companion combining outdoor/indoor routing, planning, calendar-aware context, and a Flask backend.

**Highlights**
- indoor and outdoor navigation
- multi-stop route planning
- Google Calendar integration
- mobile-first product flows
- frontend/backend test coverage

`React Native` `Expo` `TypeScript` `Python` `Flask`

</td>
<td width="50%" valign="top">

### How I approach engineering

I prefer systems that are understandable under failure, not just impressive in a demo.

**I care about:**
- explicit ownership of state
- deterministic contracts
- measured performance
- realistic recovery paths
- testing the boundaries between components
- documenting tradeoffs, not just implementation

</td>
</tr>
</table>

---

## Technical focus

| Area | Tools & technologies |
|---|---|
| **Backend** | Java, Spring Boot, Python, Node.js, REST APIs |
| **Data** | PostgreSQL, Redis, MongoDB, SQLite, Flyway |
| **Frontend** | React, React Native, TypeScript, Electron |
| **Infrastructure** | Docker, GitHub Actions, Azure |
| **ML / Data** | XGBoost, scikit-learn, tabular ML workflows |

---

### A little more about me

I’m drawn to projects that cross boundaries: backend + infrastructure, product + reliability, or ML + software architecture. I like taking a system from **“it works”** to **“it behaves predictably when things go wrong.”**

<div align="center">

**Montreal, Canada** · [LinkedIn](https://www.linkedin.com/in/mohammed-alassad/)

</div>
