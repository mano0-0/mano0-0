# Manizha Hashimi

Software engineer in Hamburg, Germany. I build and operate production backend systems on
Google Cloud — APIs, data pipelines, and the guardrails that make LLM-generated SQL safe
to execute.

**Currently:** Software Engineer at FORTYFY Music, working across TypeScript/Node.js,
Python, Angular, PostgreSQL and BigQuery.

---

### What I work on

**Natural-language analytics over a 422M-row warehouse.** An agent that lets non-technical
colleagues ask business questions in plain English, classifies each question to a governed
KPI, generates dialect-correct SQL for both BigQuery and MySQL, and joins the results
across engines. Most of the engineering went into the safety layer — because letting a
language model write SQL against production data is only as safe as what you do next.

**A film rights-licensing platform** managing distribution eligibility across 42 streaming
platforms: 85 REST endpoints over PostgreSQL, a partner-facing B2B API where each key is
scoped to exactly one platform, and an OpenAPI 3.1 contract validated in both directions.

**A multi-tenant B2B SaaS console** in Angular — white-label theming, internationalization,
and the real-browser CI gates that keep theming from breaking silently.

---

### Pinned

**[llm-sql-guard](https://github.com/mano0-0/llm-sql-guard)** — Validate LLM-generated SQL
against a policy before it reaches your database. Works on the parsed syntax tree rather
than pattern-matching the query text, so it catches a `DELETE` nested inside a CTE (which
PostgreSQL really does execute) while still allowing a query that merely contains the
string `'DROP TABLE'` in a `WHERE` clause.

---

### Tools

`TypeScript` `JavaScript` `Python` `Java` `SQL` `Dart`
`Node.js` `Express` `NestJS` `Angular` `Flutter`
`PostgreSQL` `MySQL` `BigQuery`
`Google Cloud` `Docker` `Pulumi` `GitHub Actions` `GitLab CI`
`Jest` `Vitest` `Playwright`

---

### Elsewhere

[LinkedIn](https://linkedin.com/in/manizha-hashimi) · manizhahashimi08@gmail.com

German citizen, open to US and remote roles.
