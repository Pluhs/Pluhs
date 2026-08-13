<div align="center">

# Mohammed Al Assad

### Backend systems. Full-stack products. Applied AI.

**Software Engineer in Montreal building reliable products from API to UI.**

[LinkedIn](https://www.linkedin.com/in/mohammed-alassad/) · Montreal, Canada

</div>

---

```text
mohammed@montreal:~$ what-do-you-build?

client ──► API ──► durable state ──► async work ──► observable result
                       │                  │
                       └──── recovery ◄───┘
```

I like the parts of software that get interesting when requests time out, workers restart, jobs retry, or events arrive out of order.

`Java` · `Spring Boot` · `Python` · `TypeScript` · `PostgreSQL` · `React` · `Docker`

---

## Things I’m building

<table>
<tr>
<td width="50%" valign="top">

### Asyncra
**Durable background job orchestration**

> Queues are easy. Recovery is the interesting part.

Postgres-backed asynchronous execution with retries, leases, worker heartbeats, stale recovery, side-effect fencing, SSE logs, and a TypeScript SDK.

`Spring Boot` `PostgreSQL` `TypeScript` `React`

</td>
<td width="50%" valign="top">

### AtlasML
**Local-first AutoML platform**

> ML execution without making Python own the whole product.

Electron + React on the desktop, a Spring Boot control plane, PostgreSQL as authoritative state, and bounded Python/XGBoost execution.

`Java` `Python` `React` `Electron` `PostgreSQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ConUMaps
**Mobile campus navigation & planning**

> Getting to class should not require its own graph-search problem.

A React Native campus companion with indoor/outdoor routing, multi-stop planning, calendar-aware context, and a Flask backend.

`React Native` `Expo` `TypeScript` `Python` `Flask`

</td>
<td width="50%" valign="top">

### The recurring question

**“What happens if this component stops right here?”**

That question usually leads to the engineering I enjoy most:

- explicit state ownership
- idempotency and recovery
- concurrency boundaries
- observable execution
- realistic failure paths
- measured performance

</td>
</tr>
</table>

---

## My engineering defaults

| | Default |
|---|---|
| **State** | Make ownership obvious |
| **Failures** | Make recovery boring |
| **APIs** | Prefer explicit contracts |
| **Performance** | Measure before optimizing |
| **Architecture** | Add complexity only when it earns its keep |
| **AI** | Use it where it improves the product, not where it obscures the system |

<details>
<summary><b>What I mean by “make recovery boring”</b></summary>
<br>

A repeated request should not duplicate a side effect. A restarted worker should not permanently own a job. A restarted API should not forget long-running work. A model run should be reproducible enough to explain later.

Those are the kinds of edge cases I like turning into normal system behavior.

</details>

---

<div align="center">

### Java · Spring Boot · Python · TypeScript · PostgreSQL · React · Docker

**Backend/platform engineering · distributed systems · full-stack products · ML infrastructure**

</div>
