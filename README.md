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

**Languages**

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript" title="TypeScript" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" title="JavaScript" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40" alt="Python" title="Python" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="40" height="40" alt="Java" title="Java" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dart/dart-original.svg" width="40" height="40" alt="Dart" title="Dart" />
</p>

**Backend & Frontend**

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js" title="Node.js" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" height="28" alt="Express" title="Express" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nestjs/nestjs-original.svg" width="40" height="40" alt="NestJS" title="NestJS" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/angular/angular-original.svg" width="40" height="40" alt="Angular" title="Angular" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flutter/flutter-original.svg" width="40" height="40" alt="Flutter" title="Flutter" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" width="40" height="40" alt="Tailwind CSS" title="Tailwind CSS" />
</p>

**Data**

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL" title="PostgreSQL" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="40" height="40" alt="MySQL" title="MySQL" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white" height="28" alt="BigQuery" title="BigQuery" />
</p>

**Cloud & DevOps**

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecloud/googlecloud-original.svg" width="40" height="40" alt="Google Cloud" title="Google Cloud" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" title="Docker" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pulumi/pulumi-original.svg" width="40" height="40" alt="Pulumi" title="Pulumi" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nginx/nginx-original.svg" width="40" height="40" alt="Nginx" title="Nginx" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" width="40" height="40" alt="GitHub Actions" title="GitHub Actions" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gitlab/gitlab-original.svg" width="40" height="40" alt="GitLab CI" title="GitLab CI" />
</p>

**Testing**

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jest/jest-plain.svg" width="40" height="40" alt="Jest" title="Jest" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitest/vitest-original.svg" width="40" height="40" alt="Vitest" title="Vitest" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/playwright/playwright-original.svg" width="40" height="40" alt="Playwright" title="Playwright" />
</p>

