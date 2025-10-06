# Technology Playbook

We choose tools that balance delivery speed with long-term maintainability. Every stack decision is backed by the problem we’re solving, the team who will maintain it, and the reliability targets we need to hit.

## Frontend Systems

- **React, Next.js, Remix** — component-driven interfaces with SSR/ISR options for performance and SEO.
- **Vue & Nuxt** — progressive enhancement and rapid prototyping when teams want gentle learning curves.
- **Angular + TypeScript** — structured architecture for enterprise design systems and large teams.
- **Three.js / WebGL** — immersive experiences and 3D data visualization that stay performant.
- **Tooling** — Vite, Vitest, Storybook, Playwright, Tailwind, and design token pipelines.

## Backend & Data

- **Laravel + Filament** for business platforms, internal tools, and operations dashboards.
- **Node.js / NestJS / Express** for real-time APIs, integrations, and shared TypeScript codebases.
- **Python (Django, FastAPI)** for data platforms, ML serving, and analytics backends.
- **Golang** for lightweight services that need concurrency and low-latency processing.
- **Data Layer** — PostgreSQL, PlanetScale, MongoDB, Redis, Elastic, and modern data warehouses with dbt.

## AI & Automation Stack

- **Model Integrations** — OpenAI, Anthropic, Vertex AI, Hugging Face.
- **Orchestration** — LangChain, Temporal, Airflow, bespoke agent frameworks.
- **Vector & Retrieval** — Pinecone, Supabase, pgvector, Weaviate.
- **Guardrails** — human review loops, usage analytics, policy enforcement, and audit logging.

## Cloud & Operations

- **Platforms** — AWS, GCP, Azure, Render, Vercel, and Fly.io depending on scale vs. velocity needs.
- **Containers & Orchestration** — Docker, Kubernetes, ECS, Cloud Run, serverless functions.
- **CI/CD** — GitHub Actions, GitLab CI, CircleCI with trunk-based workflows, automated quality gates, and preview environments.
- **Observability** — Datadog, Grafana, OpenTelemetry, Sentry, Loki, and custom SLO dashboards.

## Delivery Methodology

- **Agile with weekly demos** to keep stakeholder feedback continuous.
- **Shape Up-inspired planning** for focused six-week build cycles backed by two-week cooldowns.
- **Design systems + story-based development** to avoid drift between product and engineering.
- **Automated testing** across unit, integration, contract, and end-to-end layers.

## Quality & Security

- Static analysis (ESLint, PHPStan, Ruff), dependency scanning, and container image scanning in CI.
- Role-based access control, secrets management, and zero-trust architecture baked into defaults.
- Performance budgets, load testing, and chaos drills for critical systems.
- Compliance-ready practices: audit trails, data retention policies, and incident response runbooks.

## How We Decide

1. Clarify business goals and constraints.
2. Map current ecosystem and integration points.
3. Score candidate technologies on delivery velocity, scale horizon, and hiring availability.
4. Prototype risky components early, document trade-offs, and align stakeholders before committing.

Need help navigating the stack for your mission? Email **contact@synthkode.com** — we’ll set up a technical deep dive within 24 hours.