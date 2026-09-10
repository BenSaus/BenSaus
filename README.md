## Ben Sauskojus

Backend engineer in Bozeman, MT. I work on high-scale data ingestion, monetization infrastructure, and the unglamorous production reliability work that keeps both of them standing up.

Currently at **Linktree**, where I own revenue-critical backend systems on a two-engineer platform team — affiliate links, commerce ingestion, and the services underneath them.

### What that looks like

- **Ingestion at scale.** Pipelines processing 5–8M products daily across 25M+ products and 200+ brands, using streaming CSV processing and batched writes so that volume doesn't take production down with it.
- **Tooling that removes engineers from the loop.** A low-code vendor onboarding platform — sandboxed data analysis, automated PR generation via AST rewriting, a workflow state machine — that turned a two-week, engineer-gated process into ~15 minutes, with most vendors now onboarded by business development without an engineer involved.
- **Reliability work I go looking for.** A Redis-based distributed lock that cut ingest DB CPU from ~80% to ~18%. A recurring OOM crash traced to a single 2AM job by correlating schedules against crash timestamps. A delta-ingestion design using Bloom filters to eliminate millions of redundant daily writes — memory sized, false-positive risk quantified, alternatives compared before writing any code.
- **Latency where it pays.** Rearchitected a URL matching path from scrape-first to database-first with layered fallbacks, taking the common case from ~10s to under a second and driving an 88x increase in daily GMV on that surface within a month.

### Tools I reach for

`TypeScript` `Node.js` `NestJS` `PostgreSQL` `Redis` `AWS (ECS, Lambda)` `Docker` `BullMQ` `GraphQL` `Datadog` `Snowflake`

I also write C# — mostly Unity, mostly for fun.

---

Nearly everything I've built in the last five years is closed-source, so this profile is a thin slice of the work. The public repos here are mostly older side projects from an earlier freelance phase; treat them as archaeology rather than a portfolio. Happy to walk through any of the above in detail.

[LinkedIn](https://www.linkedin.com/in/ben-sauskojus-2071781b1/) · ben.sauskojus@gmail.com
