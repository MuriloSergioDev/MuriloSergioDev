# Hi, I'm Murilo Carmo 👋

**Senior Full-Stack Software Engineer** · Remote from Brazil 🇧🇷 · EST/PST Full Overlap

Senior Full-Stack Software Engineer with 7+ years of experience architecting and scaling production systems for international teams. 

Strong background in microservices, distributed systems, high-concurrency services, API design, cloud infrastructure, and performance optimization. Proven track record of leading architectural migrations, optimizing backend and database performance, building resilient services, and implementing security practices. Experienced with AI-assisted development using Claude Code and AI-powered products using OpenAI and LangChain. 

I enjoy tackling complex technical challenges, taking ownership of systems end-to-end, and collaborating with distributed teams to build reliable software that delivers real-world impact.

📬 msccarmo2@gmail.com · [LinkedIn](https://linkedin.com/in/murilo-do-carmo) · [GitHub](https://github.com/MuriloSergioDev)

---

## 🛠️ Tech Stack

**Languages**
`TypeScript` `JavaScript` `Python` `Java` `C#` `PHP` `HTML5` `CSS3`

**Frontend**
`React` `Next.js` `Angular` `AngularJS` `TailwindCSS`

**Backend**
`Node.js` `Express` `NestJS` `Laravel` `FastAPI` `Spring Boot` `.Net` `GraphQL` `REST APIs`

**AI / LLM**
`OpenAI API` `LangChain` `RAG Pipelines` `Prompt Engineering`

**Databases**
`PostgreSQL` `MongoDB` `MySQL` `SQLite`

**Cloud & DevOps**
`AWS (EC2, S3, CloudFront, Lambda)` `Docker` `Kubernetes` `GitHub Actions` `Vercel`

**Observability**
`OpenTelemetry` `Datadog` `Prometheus` `Grafana`

**Testing**
`Jest` `Playwright` `Cypress` — unit, integration & end-to-end

---

## 💼 Experience Highlights

**Zendrop** — Senior Full-Stack Engineer *(2026 – Present, West Palm Beach Florida USA · Remote)*

**Cezanne HR** — Senior Full-Stack Engineer *(2025 – 2026, London UK · Remote)*
- Defined the team’s standards for AI-assisted development (CLAUDE.md conventions, required tests and CI gates for agent-written PRs) and built evals to measure them (40 replayed tickets scored on tests, CI and review acceptance), raising agent-PR merge-without-rework rate from 52% to 74%.
- Built event-driven middleware connecting the platform to third-party payroll providers using SQS/SNS pub/sub, idempotent consumers, retries and dead-letter queues, which eliminated 88% of failed-sync support tickets and cut p95 API latency by 35%. 
- Built serverless integration endpoints on Lambda and API Gateway for webhook intake and outbound vendor call, with CloudWatch/Datadog alerting on sync failures and queue backlog. 
- Built Kafka-based asynchronous pipelines processing 2M events/day. Wrote the RFC and set the event-contract conventions now shared across the platform’s services. 
- Mentored 2 engineers on event-driven design and onboarded the team onto the agent-PR workflow; part of the on-call rotation for payroll pipelines.

**Occupop** — Senior Full-Stack Engineer *(2023 – 2025, Dublin Ireland · Remote)*
- Led the monolith-to-microservices migration: defined service boundaries, data ownership and a strangler-fig rollout, splitting off 12 services and cutting deploy time from 45 min to under 10. 
- Cut PostgreSQL p95 query time from 800 ms to 120 ms through indexing, partitioning and EXPLAIN ANALYZE tuning, reducing database CPU by 43%. 
- Modeled DynamoDB access patterns for candidate activity feeds, serving 1.5K req/s at single-digit-millisecond latency.
- Improved LCP from 4.1 s to 1.9 s with code splitting, lazy loading and caching, so every Core Web Vital passed and candidate application drop-off fell 16%. 
- Hardened API security with OAuth2 scopes, input validation and container/dependency scanning in CI, closing all high-severity pentest findings before an ISO 27001 audit.

**Techlead IT Solutions** — Software Engineer *(2022 – 2023, Brazil · Remote)*
- Built a serverless document-processing pipeline (S3 → SQS → Lambda) for PDF ingestion and ICP-Brasil digital-signature validation, handling 50K documents/month with retries and dead-letter queues. 
- Developed backend services in Java (Spring Boot) and Node.js/TypeScript for event-driven case workflows, modelling case lifecycles as explicit state machines to route work across 15 court departments. 
- Integrated with external government systems and signature-validation services through REST APIs, with role-based access control and immutable audit trails for LGPD compliance. 
- Raised test coverage from near zero to 80% by setting up unit, integration and E2E testing in CI, reducing production defects by 50%. 
- Mentored 3 junior developers through code reviews and design guidance; two were promoted to mid-level within a year.

**Bredi** — Software Engineer *(2020 – 2022, Brazil)*
- Designed a shared multi-tenant eCommerce core (catalog, cart, checkout, auth and payments as reusable modules), cutting new-store setup from 6 weeks to 2.
- Built an idempotent add-to-cart → checkout → payment flow integrating the Mercado Pago and PagSeguro APIs, using idempotency keys and webhook reconciliation to eliminate duplicate charges and orphaned orders.
- Owned the order lifecycle (created → paid → fulfilled → refunded), syncing payment-status webhooks with order state.
- Prevented overselling during flash sales with PostgreSQL row-level locking and short-lived stock reservations, handling 10x normal traffic with zero inventory mismatches.
- Cut product-listing API response time from 1.2 s to 200 ms with Redis caching, cursor pagination and indexing, improving mobile storefront performance.

---

## 🎓 Education & Certifications

- 🎓 **B.Sc. Computer Engineering** — Federal University of Pará (UFPA), 2023
- ☁️ **AWS Certified Cloud Practitioner**
- ⚛️ **Meta React Developer Certificate**

---

## 🌍 Languages

- 🇬🇧 English — C1 Professional Working Proficiency
- 🇧🇷 Portuguese — Native
